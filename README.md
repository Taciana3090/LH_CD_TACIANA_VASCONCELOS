# **INDICIUM - LIGHTHOUSE**

## **Projeto de análise cinematográfica e previsão de notas IMDb**

### **Descrição do projeto**
Este projeto faz parte de um desafio proposto pela Indicium para o estúdio de Hollywood PProductions, com o objetivo de realizar uma análise abrangente de um banco de dados cinematográfico. A análise inclui fatores que influenciam o sucesso financeiro e crítico de filmes, envolvendo análise exploratória de dados (EDA), modelagem preditiva para prever notas IMDb e recomendações estratégicas para o desenvolvimento de novas produções cinematográficas.

### **Desafio**
O desafio abrange as seguintes etapas:

#### **Análise exploratória de dados (EDA):**
- Exploração das principais características do dataset.
- Formulação de hipóteses criativas relacionadas aos dados.
- Visualização de padrões e relações entre variáveis.

#### **Questões a serem respondidas:**
- Qual filme você recomendaria para uma pessoa que você não conhece?
- Quais são os principais fatores relacionados com alta expectativa de faturamento de um filme?
- Quais insights podem ser obtidos com a coluna Overview? É possível inferir o gênero do filme a partir dessa coluna?

#### **Previsão da nota IMDb:**
- Método utilizado para prever a nota IMDb.
- Discussão sobre variáveis utilizadas, transformações aplicadas e tipo de problema abordado (regressão).
- Comparação e justificação do modelo final escolhido entre diferentes modelos de machine learning (LightGBM, CatBoost, etc.).

#### **Avaliação de filme hipotético:**
- Determinação da nota IMDb para um filme hipotético com base em características específicas fornecidas.

#### **Recomendações para pesenvolvimento de filme:**
- Estratégias recomendadas com base nos insights obtidos.

### **Pré-requisitos**
Certifique-se de ter Python 3.11.9 instalado em sua máquina. Você pode baixá-lo e instalá-lo a partir do [site oficial do Python](https://www.python.org/downloads/release/python-3119/).

### **Instalação**

1 - **Clone este repositório manualmente ou via terminal:**
```bash
git clone https://github.com/Taciana3090/LH_CD_TACIANA_VASCONCELOS.git
cd LH_CD_TACIANA_VASCONCELOS
```

2 - **Crie e ative um ambiente virtual (recomendado):**
```bash
python -m venv env
source env/bin/activate   # No Windows use `env\Scripts\activate`
```

3 - **Instale as dependências:**
```bash
pip install -r requirements.txt
```

### **Como executar:**

1 - Para executar o Jupyter Notebook:
```bash
jupyter notebook
```
- Isso abrirá o jupyter notebook no seu navegador. Navegue até o arquivo `projeto_imdb.ipynb` e abra-o.

2 - Execute o Script Python

### **Dependências**
As principais bibliotecas utilizadas neste projeto são:

- pandas
- numpy
- seaborn
- matplotlib
- termcolor
- scikit-learn
- lightgbm
- catboost
- xgboost
- joblib
  
Todas as dependências estão listadas no arquivo requirements.txt.

### **Estrutura de Pastas:**

- `data/`: Contém os arquivos:
  - `desafio_indicium_imdb.csv`: Base de dados.
  - `[Lighthouse] Desafio Ciência de Dados 2024-9.pdf`: Documento relacionado ao desafio de Ciência de Dados.
- `image/`: Figuras geradas durante a análise, como nuvens de palavras.
- `models/`: Modelos de regressão automaticamente salvos. Se a pasta não existir, crie manualmente para evitar erros nos passos seguintes do código.



### **Contato**

Para mais informações ou feedback sobre este projeto, entre em contato:

-  [Taciana Vasconcelos](taciana3090@gmail.com)

- [LinkedIn](https://www.linkedin.com/in/taciana-v-44a929217/)





