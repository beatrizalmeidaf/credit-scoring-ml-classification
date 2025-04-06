# Practical Task of Classification (Machine Learning)

# ![Image](https://github.com/user-attachments/assets/fa7f02c2-d5e2-4b25-bb67-bcae1e3be72b)

## 📌 Sobre o Projeto
Esse projeto tem como objetivo desenvolver um modelo de classificação para concessão de crédito utilizando aprendizado de máquina. A partir do arquivo `dados.csv`, o projeto passa por diversas etapas, desde a análise exploratória dos dados até a criação de um dashboard interativo no Power BI.

## 🚀 Etapas do Projeto

###  1. Importação e Configuração
**Objetivo:** Importar bibliotecas necessárias para o desenvolvimento do projeto.
 
### 2. Análise Exploratória de Dados (EDA)
**Objetivo:** Compreender a estrutura dos dados, identificar padrões e detectar anomalias.
- Carregamento dos dados
- Visualização da distribuição das variáveis 
- Identificação de outliers 
- Análise de correlação entre variáveis 
- Resumo estatístico das variáveis
- Visualização de dados categóricos e numéricos 

### 3. Pré-processamento de Dados
**Objetivo:** Preparar os dados para o modelo de aprendizado de máquina.
- Tratamento de outliers 
- Codificação de variáveis categóricas
- Normalização/Escala das variáveis numéricas
- Divisão dos dados em treino e teste

### 4. Engenharia de Atributos (Feature Engineering)
**Objetivo:** Criar novas variáveis que possam melhorar a performance do modelo.
- Criação de novas features a partir das existentes 
- Seleção das features mais relevantes 
- Transformação de features (log, raiz quadrada, etc.) 
- Análise da importância das features 

### 5. Treinamento do Modelo de Classificação
**Objetivo:** Treinar um modelo de machine learning para prever a concessão de crédito.
- Escolha do algoritmo de classificação 
- Treinamento do modelo 
- Avaliação do modelo (acurácia, precisão, recall) 
- Ajuste de hiperparâmetros
- Validação cruzada 

### 6. Interpretação e Comunicação dos Resultados
**Objetivo:** Interpretar os resultados do modelo e comunicar conclusões de forma clara.
- Interpretação dos resultados do modelo
- Visualização dos resultados (matriz de confusão, curva ROC) 
- Relatório final com conclusões e recomendações 
- Discussão de possíveis melhorias no modelo 
- Apresentação dos resultados para um público não técnico  

## 📦 Instalação e Configuração do Ambiente
Para configurar o ambiente e garantir a reprodutibilidade dos experimentos, foi utilizado o **Conda**.

### 1. Criar e ativar o ambiente Conda:
```bash
conda create -n classificacao_credito python=3.9 -y
conda activate classificacao_credito
```

### 2. Instalar as dependências do projeto:
```bash
pip install -r requirements.txt
```

## 🛠️ Ferramentas Utilizadas  

- **Linguagem:** Python  
- **Principais bibliotecas:**  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  
  - statistics  
- **Versionamento:** Git 

