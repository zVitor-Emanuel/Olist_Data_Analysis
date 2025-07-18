# Olist Data Project 
O notebook deve ser executado no Jupyter Lab ou Preferencialmente no Jupyter VSCODE.


Este projeto foi desenvolvido como parte do **Teste Técnico do Bootcamp - Programa Trainee triggo.ai** para a área de **Engenharia de Dados e DataOps**. O objetivo é simular um cenário real de trabalho com dados de e-commerce, aplicando técnicas de **Python, SQL, modelagem de dados, visualização e análise de negócio**.

---
## Como Executar

1. Clone este repositório
2. Instale os requisitos(pandas, numpy, seabor, matplotlib, sckit-learn, sqlite3, ipython-sql, plotly, ipywidgets, ipython-display)
3. Utilize preferencialmente o Jupyter no VSCODE ou Jupyter Lab para rodar o notebook. Pode apresentar problemas no dashboard na versão antiga do jupyter notebook.

---

---

## 🎯 Objetivo

Você foi contratado como Engenheiro de Dados Júnior em uma empresa de e-commerce brasileira. Sua tarefa é explorar o histórico de vendas, realizar análises e gerar insights para o negócio, com base nos dados públicos da Olist.

---

## 📦 Dataset

Utilizado o **Brazilian E-commerce Public Dataset by Olist**, disponível no Kaggle:

🔗 [Link para o dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)

- +100.000 pedidos entre 2016 e 2018
- Dados de pedidos, clientes, produtos, vendedores, pagamentos, avaliações e localização

---

## 🛠️ Tecnologias e Ferramentas

- **Python**: pandas, numpy, matplotlib, seaborn, plotly, ipywidgets, IPython
- **SQL**: sqlite3, ipython-sql
- **Machine Learning**: scikit-learn
- **Ambiente**: Jupyter Lab / VSCode

---

## 🧪 Estrutura do Projeto

### 1. Preparação dos Dados

- Leitura dos arquivos CSV
- Tratamento de dados ausentes e duplicados
- Conversão de datas e normalização de colunas
- Criação de modelo relacional entre tabelas
- Documentação das etapas

### 2. Análise Exploratória

- Sazonalidade: maior volume de vendas entre março e agosto
- Entregas: maioria entre 0 e 50 dias, com picos no 7º dia
- Frete: custo aumenta com a distância entre cliente e vendedor
- Produtos: categorias "beleza_saude" e "relogios_presentes" lideram em faturamento
- Localização: Paraíba tem maior ticket médio; São Paulo, maior volume de compras

### 3. Soluções de Negócio

- **Retenção de Clientes**: baixa taxa de recompra
- **Atraso na Entrega**: modelo preditivo pouco eficaz (99% das entregas pontuais)
- **Segmentação de Clientes**: 4 perfis distintos com base em gasto e avaliação
- **Satisfação**: tempo de entrega é o fator mais relevante

### 4. Dashboards

- Construção de dashboards interativos dentro do notebook para visualizar os insights.

---

### Veja o notebook completo:

📄 [Códigos, insights e visualizações](https://github.com/zVitor-Emanuel/Olist_Data_Analysis/blob/main/case.ipynb)
