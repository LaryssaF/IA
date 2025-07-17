# Projeto de IA: Previsão de Vencedores em Lutas
Este projeto tem como objetivo aplicar técnicas de Inteligência Artificial para prever o possível vencedor de uma luta com base em dados históricos dos lutadores e estatísticas das lutas anteriores. A análise envolve pré-processamento de dados, seleção de atributos, treinamento de modelos de machine learning e validação de desempenho.

📊 Objetivo do Projeto
Desenvolver um modelo preditivo capaz de estimar o vencedor de uma luta com base em:

Características físicas e técnicas dos lutadores;

Histórico de vitórias/derrotas;

Estilo de luta;

Dados estatísticos como precisão de golpes, quedas, finalizações e resistência.

📁 Estrutura do Projeto
bash
Copiar
Editar
/data                → Conjunto de dados original e tratado  
/analysis            → Análises exploratórias (EDA) e visualizações  
/models              → Treinamento e avaliação de modelos de ML  
/notebooks           → Jupyter Notebooks explicativos  
/docs                → Documentação técnica e explicações teóricas  
main.py              → Script principal para execução do pipeline  
requirements.txt     → Dependências do projeto
🧾 Fonte dos Dados
Utilizamos um dataset contendo lutas do UFC (Ultimate Fighting Championship), com mais de 5.000 registros contendo:

Nome dos lutadores

Altura, peso, alcance, idade

Estatísticas de golpes, defesas, quedas e finalizações

Resultado da luta (vencedor/perdedor)

🧹 Pré-processamento
Etapas realizadas:

Limpeza de dados: Remoção de nulos, correção de inconsistências e transformação de tipos.

Feature engineering:

Criação de variáveis como “diferença de idade” ou “experiência relativa”.

Normalização e padronização de atributos.

Codificação de variáveis categóricas (OneHot, LabelEncoder).

Balanceamento de classes, quando necessário (por exemplo, usando SMOTE).

🔍 Análise Exploratória (EDA)
Distribuição de vitórias por idade, altura e peso.

Correlação entre estatísticas e resultado.

Identificação de atributos mais relevantes para a vitória.

Visualizações com Matplotlib, Seaborn e Plotly.

🤖 Modelos Utilizados
Foram testados e comparados diferentes algoritmos de classificação:

🧩 Árvore de Decisão

📍 K-Nearest Neighbors (KNN)

📈 Regressão Logística

Critérios avaliados:

Acurácia
Matriz de confusão

Conclusão 

O modelo é capaz de fazer previsões com boa precisão, especialmente quando os lutadores possuem perfis bem distintos.

Algumas estatísticas, como eficiência de golpes e defesa, têm grande impacto no resultado.

A IA pode ser usada como ferramenta de apoio para análises esportivas, apostas, ou simplesmente para entender melhor os padrões do esporte.

