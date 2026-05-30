# Análise de E-commerce Brasileiro — Olist

## Sobre o Projeto
Análise exploratória de dados reais de uma plataforma brasileira de e-commerce com mais de 99 mil pedidos realizados entre 2016 e 2018. O objetivo é extrair insights de negócio sobre comportamento de clientes, categorias de produtos, satisfação e logística.

## Perguntas Respondidas
- Quais estados brasileiros concentram mais clientes?
- Quais categorias de produtos são mais vendidas?
- Como está a satisfação geral dos clientes?
- Em quais períodos as vendas são maiores?
- Quais estados têm o maior tempo médio de entrega?

## Principais Insights
- **São Paulo** concentra mais de 40% dos clientes, quase o triplo do segundo colocado (RJ)
- **Cama, mesa e banho** é a categoria mais vendida, seguida de beleza e saúde
- A média de avaliações é **4.09 de 5**, mas mais de 11 mil clientes deram nota 1
- O pico de vendas ocorre em **novembro**, coincidindo com a Black Friday
- **Roraima** tem o pior tempo de entrega — quase 29 dias contra 8 dias de SP

## Tecnologias Utilizadas
- Python 3
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

## Como Reproduzir o Projeto

1. Clone o repositório:
```bash
git clone https://github.com/seu-usuario/olist-ecommerce-analisys.git
```

2. Instale as dependências:
```bash
pip install pandas matplotlib seaborn plotly
```

3. Baixe o dataset em: [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

4. Coloque os arquivos CSV na pasta `data/raw/`

5. Execute o notebook `notebooks/01_eda.ipynb`

## Fonte dos Dados
[Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce) — disponível publicamente no Kaggle.