# ecommerce-visualizacoes

Visão Geral

Este projeto contempla o desenvolvimento completo de um pipeline analítico, desde a exploração e tratamento dos dados até a construção de uma aplicação interativa utilizando Dash.

A proposta foi estruturar uma base de dados, aplicar técnicas de análise exploratória (EDA) e disponibilizar os insights por meio de um dashboard dinâmico e orientado à tomada de decisão.

O repositório está organizado em dois notebooks principais:

Exercicio.ipynb → Data Wrangling, EDA e modelagem analítica

aplicação_Dash.ipynb → Desenvolvimento da aplicação interativa com Dash

🧹 1. Data Preparation & Exploratory Data Analysis

No notebook Exercicio.ipynb, foram executadas as seguintes etapas:

🔹 Data Wrangling

Leitura e estruturação da base

Tratamento de valores ausentes

Conversão de tipos de variáveis

Padronização de colunas

Criação de variáveis derivadas

🔹 Análise Exploratória (EDA)

Análise estatística descritiva

Distribuição das variáveis

Identificação de padrões e outliers

Correlação entre variáveis relevantes

Construção de métricas estratégicas

🔹 Visualizações

Gráficos exploratórios com Plotly

Comparações por categoria

Análises temporais (quando aplicável)

Essa etapa teve como objetivo garantir qualidade dos dados e extrair insights estruturais antes da construção da camada de visualização.

📈 2. Dashboard Interativo com Dash

O notebook aplicação_Dash.ipynb implementa uma aplicação web utilizando Dash para disponibilização dos insights.

🔹 Estrutura da Aplicação

Definição do layout com componentes HTML e Core Components

Organização modular dos gráficos

Estruturação de filtros interativos

🔹 Interatividade

Implementação de callbacks

Atualização dinâmica de gráficos com base em filtros

Manipulação eficiente do dataframe para resposta em tempo real

🔹 Visual Analytics

Indicadores principais (KPIs)

Gráficos comparativos

Análises segmentadas

Visualização orientada à tomada de decisão

🛠 Stack Tecnológica

Python

Pandas → Manipulação e transformação de dados

Plotly → Visualização interativa

Dash → Construção da aplicação web

Jupyter Notebook

🧠 Competências Demonstradas

Data Cleaning & Data Wrangling

Exploratory Data Analysis (EDA)

Feature Engineering

Construção de métricas analíticas

Data Visualization

Desenvolvimento de dashboards interativos

Estruturação de aplicações analíticas em Python

🚀 Execução do Projeto
# Clonar repositório
git clone <url-do-repositorio>

# Instalar dependências
pip install -r requirements.txt

# Executar análise
Exercicio.ipynb

# Executar aplicação
aplicação_Dash.ipynb
