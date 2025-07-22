# 📊 Projecto 01: Análise Exploratória de Dados de Vendas

> *Projeto de Ciência de Dados | Python, Pandas, Matplotlib, Seaborn*

Este projeto realiza uma **análise exploratória completa (EDA)** a partie de um conjunto de dados fictícios de vendas, com o objetivo de identificar padrões, tendências e insights acionáveis que possam apoiar decisões de negócio. Os dados simulam operações de uma empresa distribuidora localizada em Moçambique e países vizinhos.

---

## 🎯 Objetivos do Projecto

- Compreender a distribuição das vendas por região, produto, vendedor e período.
- Identificar os produtos mais vendidos e as regiões com maior volume de negócios.
- Visualizar tendências ao longo do tempo e desempenho dos representantes de vendas.
- Aplicar boas práticas de limpeza, análise e visualização de dados com Python.

---

## 🛠 Tecnologias Utilizadas

| Ferramenta | Uso |
|----------|-----|
| **Python** | Linguagem principal |
| **Pandas** | Manipulação e análise de dados |
| **NumPy** | Operações numéricas |
| **Matplotlib / Seaborn** | Visualização de dados |
| **Jupyter Notebook** | Ambiente de desenvolvimento |
| **CSV** | Formato do dataset |

---

## 📁 Dataset

- **Nome:** `sales_data.csv`
- **Fonte:** Dados fictícios gerados para fins educativos
- **Registos:** 1.000 linhas
- **Colunas:** 9 (OrderID, Date, Region, Product, Quantity, UnitPrice, TotalSales, SalesRep, PaymentMethod)
- **Período:** Janeiro a Dezembro de 2024

📌 *O dataset foi gerado programaticamente para simular um cenário realista de vendas na região da África Austral.*

---

## 🧠 Metodologia

1. **Carregamento dos dados** com `pandas`
2. **Limpeza e validação**: verificação de valores nulos, tipos de dados
3. **Análise descritiva**: médias, totais, distribuições
4. **Agregações por categoria**: região, produto, vendedor
5. **Visualizações**:
   - Gráfico de barras: vendas por região
   - Gráfico de linhas: evolução mensal das vendas
   - Boxplot: distribuição de quantidades por produto
   - Tabela dinâmica: vendas por vendedor e região
6. **Extração de insights** com base nos resultados

---

## 📈 Principais Insights

✅ **Região com mais vendas:** Johannesburg (maior volume de TotalSales)  
✅ **Produto mais vendido:** Smartphone (alta frequência e bom valor unitário)  
✅ **Melhor vendedor:** Carla Nunes (maior faturação total)  
✅ **Mês de pico:** Novembro (possível sazonalidade de fim de ano)  
✅ **Método de pagamento predominante:** Multicaixa (reflete hábitos locais)

> Estes insights podem orientar decisões como alocação de estoque, campanhas promocionais e incentivos a vendedores.

---

## 🖼 Exemplos de Visualizações

| Gráfico | Descrição |
|-------|-----------|
| ![Vendas por Região](plots/sales_by_region.png) | Distribuição do faturamento por região |
| ![Tendência Mensal](plots/monthly_trend.png) | Evolução das vendas ao longo do tempo |

> *(As imagens devem ser salvas na pasta `/plots` após execução do notebook)*

---

## 📦 Como Executar o Projeto

### Pré-requisitos
- Python 3.8 ou superior
- Jupyter Notebook (ou VS Code/Google Colab)

### Passos:

1. Clone o repositório:
   ```bash
   git clone https://github.com/MMucelo/data-analysis-sales.git 
