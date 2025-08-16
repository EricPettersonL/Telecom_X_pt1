# 📊 Análise de Evasão de Clientes (Churn) - Telecom X

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google%20Colab-F9AB00?logo=googlecolab&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Data%20Viz-009688)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Charts-11557c)

---

## 📌 Sobre o Projeto
Este projeto tem como objetivo analisar os dados de clientes da **Telecom X** para entender os fatores que influenciam a **evasão de clientes (Churn)**.  
Com base nos dados fornecidos pela empresa, realizamos desde a **limpeza e preparação dos dados** até a **análise exploratória** e **extração de insights estratégicos**.

---

## 🛠️ Tecnologias Utilizadas
- **Python 3**  
- **Google Colab**  
- **Bibliotecas**:  
  - Pandas  
  - NumPy  
  - Matplotlib  
  - Seaborn  

---

## 📂 Estrutura do Projeto
  *  TelecomX_Data.json → Dados brutos da API
  *  notebook.ipynb → Notebook principal com análise e visualizações
  *  README.md → Documentação do projeto
---

---

## 📊 Etapas do Trabalho

### 1️⃣ Introdução
- **Problema de Churn**: alta taxa de cancelamentos impacta diretamente no faturamento da Telecom X.  
- **Objetivo**: identificar padrões e fatores relacionados ao cancelamento.  

### 2️⃣ Limpeza e Tratamento de Dados
- Importação dos dados em JSON via API.  
- Normalização de colunas aninhadas.  
- Correção de valores ausentes na variável `Churn`.  
- Conversão de respostas categóricas (`Yes/No → 1/0`).  
- Criação da variável **Contas_Diarias** (baseada no faturamento mensal).  

### 3️⃣ Análise Exploratória
- Distribuição geral da evasão (`Churn`).  
- Relação do churn com variáveis categóricas (gênero, contrato, pagamento).  
- Análise percentual das categorias.  
- Comparação de variáveis numéricas (`TotalGasto`, `tenure`) entre clientes que saíram e permaneceram.  

### 4️⃣ Conclusões e Insights
- Clientes com **contratos mensais** e **pagamento eletrônico** têm maior propensão à evasão.  
- Quanto maior o **tempo de contrato**, menor a chance de churn.  
- Clientes com **baixo gasto total** também tendem a cancelar mais cedo.  

### 5️⃣ Recomendações
- Criar incentivos para contratos **anuais**.  
- Melhorar a experiência de clientes com **pagamentos eletrônicos**.  
- Oferecer descontos ou benefícios para **clientes novos (baixa tenure)** a fim de reduzir cancelamentos precoces.  

---

## 📈 Exemplos de Visualizações
📌 Alguns gráficos desenvolvidos no projeto:  

- Distribuição do churn  
- Evasão por tipo de contrato  
- Evasão por método de pagamento  
- Boxplots comparando variáveis numéricas  

---
##🚀 Como Executar o Projeto

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
```

2. Abra no Google Colab ou Jupyter Notebook.

3. Instale as dependências (se necessário):
```bash
pip install pandas numpy matplotlib seaborn
```

4. Execute o notebook para reproduzir as análises.

👤 Autor

Seu Nome
🔗 LinkedIn | GitHub
