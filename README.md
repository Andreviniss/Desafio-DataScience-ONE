# 📂 Análise de Vendas - Alura Store Brasil

Este repositório contém uma análise exploratória de dados (EDA) focada no desempenho de vendas de diferentes filiais da **Alura Store Brasil**. O projeto utiliza Python para processar bases de dados, gerar insights sobre faturamento e visualizar tendências de mercado.

## 🚀 Objetivo do Projeto

O principal objetivo deste notebook é consolidar os dados de vendas de múltiplas lojas e realizar uma análise comparativa para responder:

* Qual é o faturamento bruto por loja?
* Qual a tendência de faturamento mensal da rede versus lojas individuais?
* Quais são as categorias de produtos mais vendidas nas lojas de melhor e pior desempenho?
* Qual o impacto do custo de frete no faturamento total?

## 🛠️ Tecnologias e Bibliotecas

As seguintes ferramentas foram utilizadas no desenvolvimento deste projeto:

* **Python 3**
* **Pandas**: Manipulação e tratamento de dados.
* **Matplotlib**: Criação de gráficos estáticos.
* **Seaborn**: Visualizações estatísticas personalizadas.
* **Numpy**: Operações matemáticas e suporte a arrays.

## 📊 Principais Análises Realizadas

1. **Importação e Limpeza**: Carregamento de arquivos CSV hospedados externamente e verificação de tipos de dados (Datas, Preços, Categorias).
2. **Análise de Faturamento Bruto**: Agrupamento dos dados por loja para identificar a unidade com maior receita.
3. **Sazonalidade e Tendências**: Gráficos de linha mostrando a evolução mensal do faturamento, permitindo identificar picos de vendas ao longo do ano.
4. **Distribuição de Categorias**: Identificação do "Top 3" categorias de produtos por loja (ex: eletrônicos, móveis, brinquedos).
5. **Indicadores Logísticos**: Cálculo do valor médio de frete por unidade para entender a eficiência logística regional.

## 📈 Resultados e Insights

* **Faturamento**: A análise permitiu visualizar disparidades entre as lojas, com a "Loja 1" apresentando um faturamento bruto superior a R$ 1,5 milhão no período analisado.
* **Comportamento do Consumidor**: Categorias como **eletrônicos** e **móveis** aparecem com frequência entre os itens mais vendidos.

## 💻 Como executar o projeto

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/alura-store-brasil.git

```


2. Instale as dependências necessárias:
```bash
pip install pandas matplotlib seaborn numpy

```


3. Abra o arquivo `AluraStoreBrasil (2).ipynb` no Jupyter Notebook ou Google Colab.

---

### 📝 Estrutura de Arquivos

* `AluraStoreBrasil (2).ipynb`: Notebook principal com todo o código e visualizações.

---

**Autor:** André Vinicius Silva Santos
**LinkedIn:** www.linkedin.com/in/andreviniss
