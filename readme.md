# Olist Data Project 
O notebook deve ser executado no Jupyter Lab ou Preferencialmente no Jupyter VSCODE.


Este projeto foi desenvolvido como parte do **Teste Técnico do Bootcamp - Programa Trainee triggo.ai** para a área de **Engenharia de Dados e DataOps**. O objetivo é simular um cenário real de trabalho com dados de e-commerce, aplicando técnicas de **Python, SQL, modelagem de dados, visualização e análise de negócio**.

---
## Como Executar

1. Clone este repositório
2. Instale os requisitos(pandas, numpy, seabor, matplotlib, sckit-learn, sqlite3, ipython-sql, plotly, ipywidgets, ipython-display)
3. Utilize preferencialmente o Jupyter no VSCODE ou Jupyter Lab para rodar o notebook. Pode apresentar problemas no dashboard na versão antiga do jupyter notebook.

---

##  Objetivo

Você foi contratado como Engenheiro de Dados Júnior em uma empresa de e-commerce brasileira. Sua primeira tarefa é explorar o histórico de vendas, realizar análises e gerar insights estratégicos para o negócio, com base no conjunto de dados públicos da Olist.

---

##  Dataset

Utilizei o **Brazilian E-commerce Public Dataset by Olist**, disponível no Kaggle:

🔗 [Acesse o dataset no Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

- +100.000 pedidos realizados entre 2016 e 2018
- Dados de pedidos, clientes, produtos, vendedores, pagamentos, avaliações e localização

---

## Tecnologias e Ferramentas

- Python (pandas, numpy, matplotlib, seaborn, plotly, ipywidgets, ipython.display)
- SQL (ipython-sql e sqlite3)
- Visualizações com Plotly, Seaborn e matplotlib
- Modelagem Relacional com Pandas
- Scikit-learn para Machine Learning
- Jupyter Lab

---

## 🧪 Estrutura do Projeto

### 1. 📋 Preparação dos Dados

- Importação e exploração inicial dos arquivos CSV
- Tratamento de valores ausentes, remoção de duplicatas
- Conversão de formatos de data e normalização de colunas
- Criação de um modelo relacional entre as tabelas
- Documentação de todas as etapas

### 2. 📊 Análise Exploratória de Dados

- Na Análise de dados descobri métricas importantes:
  1. A sazonalidade das vendas é muito maior durante Março-Agosto, e Muito Menor de Setembro-Dezemebro. O que nos possibilia preparar estoque de produtos para se adequar com a demanda necessária.
  2. A distribuição de entrega esta entre 0-50 dias, com maior recorrência de entregas no sétimo dia e com outlier que chegaram a demorar 200 dias para serem entreges.
  3. Conforme a distância entre o Vendedor e o Cliente aumenta, maior é o frete pago.
  4. Os pedidos mais vendidos em termos de faturamento são os de beleza_saude e relogios_presentes
  5. O estado da paraíba apresenta o maior valor médio por produto, enquanto são paulo apresenta a maior quantidade de compras de produtos.
 
### 3. 🧠 Solução de Problemas de Negócio

- **Análise de Retenção de Clientes:** A retenção dos clientes é muito baixa, tendo muitos clientes que compram uma única vez e pouquissmos clientes que compram mais de 1 produto
- **Predição de Atraso na Entrega:** O modelo de predição de atraso não foi muito acertivo, pois 99% dos dados foram entregues na data estipulada na compra.
- **Segmentação de Clientes:** Temos 4 tipos de clientes, desde os que gastam muito e avaliam bem até os que gastam pouco e avaliam muito mal.
- **Análise de Satisfação:** O principal fator de satisfação dos cliente é no tempo de entrega.

### 4. 📈 Dashboards e Visualizações

- Na parte de dashboard e visualizações tentei construir de forma que ligasse todos os insights obtidos nas análises de forma visual e interativa, para que stakeholders conseguissem utilizar e entender os dados.

---





