# Análise de Dados com Python

Análise de dados fictícios com Python. Projeto desenvolvido durante a Jornada Python da Hashtag Treinamentos.

## Sobre o projeto

Este projeto analisa uma base de dados de clientes de uma empresa com mais de 800 mil clientes. A empresa identificou que a maioria dos seus clientes está inativa (cancelou o serviço) e deseja entender os principais motivos dos cancelamentos e quais ações são mais eficientes para reduzi-los.

## Objetivo

Identificar as causas dos cancelamentos e propor ações para diminuir a taxa de cancelamento (churn) da empresa.

## Tecnologias utilizadas

- Python 3
- Pandas (manipulação e análise de dados)
- Plotly Express (visualização de dados)
- Jupyter Notebook

## Estrutura do projeto

- `inicial.ipynb` — notebook com o enunciado do case
- `analise.ipynb` — notebook com a análise completa
- `cancelamentos.csv` — base de dados fictícia utilizada na análise

## Passos da análise

1. Importar a base de dados
2. Visualizar a base de dados
3. Corrigir problemas da base (valores vazios, colunas desnecessárias)
4. Análise inicial dos cancelamentos
5. Análise das causas dos cancelamentos com gráficos
6. Propostas de ações para reduzir os cancelamentos

## Principais conclusões

- Clientes com contrato mensal cancelam em massa — oferecer desconto nos planos anuais e trimestrais.
- Clientes que ligam mais de 4 vezes ao call center tendem a cancelar — criar processo para resolver o problema em no máximo 3 ligações.
- Clientes com mais de 20 dias de atraso cancelam — política de resolução de atrasos em até 10 dias.

Após aplicar essas ações, a taxa de cancelamento caiu de 56,8% para 18,4%.

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/fernandonavarrost-cpu/analise_dados_py.git
   ```

2. Instale as dependências:
   ```bash
   pip install pandas numpy plotly openpyxl nbformat ipykernel
   ```

3. Abra o notebook `analise.ipynb` no Jupyter e execute as células.

## Créditos

Projeto baseado no material da [Hashtag Treinamentos](https://www.hashtagtreinamentos.com/).

