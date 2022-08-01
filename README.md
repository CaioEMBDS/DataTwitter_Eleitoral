# Projeto Prático - DataTwitter Eleitoral

Created: July 31, 2022 11:26 AM

## Etapa 1 - Entendendo o problema

---

- Análise de Sentimentos
- Proposta para a construção de uma aplicação que realiza análise de sentimentos dos candidatosà presidência
- Análise de Sentimentos - Extração de sentimentos a partir de um texto (Positivo, Negativo, Neutro)
- Relação com o cliente/consumidor - (Reclame Aqui, Amazon, etc)
- Inteligência Artificial
- Linguagem: Python

## Etapa 2 - Coletando os Dados

---

# 🧩Etapa 2 - Coletando os Dados

- Dados estão em todo lugar e são a *matéria-prima da informação*
    - Todo dia produzimos mais dados → drones, apps, browser, câmeras, localização, etc.
    - 5Vs (Volume, Velocidade, Variedade, Veracidade e Valor)
    - 2.5 quintilhões de bytes de dados todos os anos
    - Mais dados foram coletados nos últimos anos do que em toda a história da humanidade
    
    ## O novo petróleo ⛽📈
    
    - *Para onde vão todos esses dados criados? Como organizar, acessar, manipular esses dados?*
        - Planilhas Eletrônicas, Bancos de dados, Arquivos CSV, ERP, APIs
    - Vamos fazer uma pesquisa e descobrir onde conseguir esses dados
    - Buscando por APIs:
    
    [Documentation Home](https://developer.twitter.com/en/docs)
    
    - Codando:

## Etapa 3 - EDA, Storytelling e Visualização

---

- Aqui damos sentido aso dados
- *70% a 80% do tempo do projeto*
- Quais dados temos? qual tipo? precisamos fazer limpeza de dados? tem dados faltantes? outliers, inconsistência
- Bibliotecas importantes para Análise de Dados:

[pandas](https://pandas.pydata.org/)

- Bibliotecas importantes para Visualização de Dados:

[Tutorials - Matplotlib 3.5.2 documentation](https://matplotlib.org/stable/tutorials/index.html)

[seaborn: statistical data visualization - seaborn 0.11.2 documentation](https://seaborn.pydata.org/)

## Etapa 4 - Análise de Sentimentos

---

- A análise de sentimento (ou mineração de opinião) é uma técnica de [processamento de linguagem natural (PNL)](https://monkeylearn.com/natural-language-processing/) usada para determinar se os dados são positivos, negativos ou neutros.
- Ajuda as empresas a monitorar o sentimento da marca e do produto de acordo com o comentário do cliente

## Etapa 5 - Deploy

---

- Quando terminamos uma aplicação, em qualquer lugar podemos disponibilizar para outras pessoas acessarem?
- Coletar e analisar dados é uma coisa, mas colocar uma aplicação no ar é outra
- Nós vamos precisar de um servidor de produção:
    - Um tipo de servidor usado para implantar e hospedar sites ou aplicativos
- Comece pelo simples:

[Streamlit * The fastest way to build and share data apps](https://streamlit.io/)

- Outras ferramentas:

[Home - Docker](https://www.docker.com/)

[Welcome to Flask - Flask Documentation (2.1.x)](https://flask.palletsprojects.com/en/2.1.x/)

[Dremio | The Easy and Open Data Lakehouse Platform](https://www.dremio.com/)
