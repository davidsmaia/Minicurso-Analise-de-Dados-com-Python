# **Minicurso Analise de Dados com Python - Hashtag Treinamentos**
Projeto realizado durante o minicurso **"Análise de Dados com Python** da [Hashtag Treinamentos](https://www.hashtagtreinamentos.com/)


## **Contexto:** 
Em uma determinada empresa de cartão de crédito, o diretor solicitou uma análise para identificar os motivos dos cancelamentos e propor soluções


## **Objetivo:**
- Identificar o motivo dos cancelamentos
- Sugerir ações para reduzir a perda de clientes


## **Tecnologias Utilizadas:**

- **Python** (Pandas, Plotly Express)
- **Jupyter Notebook** (VS Code)


## **Estrutura do Projeto:**

-> Gabarito - Minicurso Analise de Dados Python.ipynb # Solução oficial

-> solucao.ipynb # **Minha versão com anotações e melhorias**

-> ClientesBanco.csv # Base de dados


## **Principais Análises e Insights:**

### 1. Categoria do Cartão
- **A grande maioria dos cancelamentos** ocorre com clientes que possuem cartão da categoria Blue

### 2. Número de Produtos Contratados
- **Quanto mais produtos** o cliente tem, menor é a taxa de cancelamento

### 3. Transações Financeiras
- **Cancelamentos tendem a ocorrer quando:**
    - **Menos transações** (< 60 nos últimos 12 meses)
    - **Valores menores** (< $3.200).

### 4. Contatos com o Serviço de Atendimento
- **Cancelamentos são proporcionais ao número de contatos**:  
  - Clientes que entraram em contato **6 vezes** tiveram **100% de cancelamento**. 


## **Novas implementações / Melhorias:**

1 - **Dicionário de gráficos**
    - Agora é possível acessar e visualizar cada gráfico pelo nome da coluna:

    """
    display(graficos_dict["Estado Civil"])
    """

2 - **Menu iterativo**
    - O usuário pode escolher qual coluna analisar via input numérico
    
3 - **Tratamento de erros**
    - Evita erros se a opção digitada for inválida


## **Links Úteis:**

[3 Projetos em Python para Iniciantes - Hashtag Programação](https://www.youtube.com/watch?v=tLFT40Xrhq0)

[Curso: PROJETO 2](https://dlp.hashtagtreinamentos.com/python/minicurso/minicurso-analise-de-dados/inscricao?curso=python&origemurl=hashtag_yt_org_minipython_tLFT40Xrhq0&utm_campaign=programacao&utm_content=python%2Fminicurso%2Fminicurso-analise-de-dados%2Finscricao&conversion=lespy-May-25)

[Base de Dados Original](https://www.kaggle.com/sakshigoyal7/credit-card-customers)
[Hashtag Treinamentos](https://www.hashtagtreinamentos.com/)
