# Universities API ETL

Este projeto demonstra um pequeno pipeline de dados utilizando conceitos de **Engenharia de Dados**.

O objetivo é extrair dados de uma API pública de universidades, transformá-los e armazená-los em um banco de dados relacional para consultas futuras.

## Tecnologias utilizadas

- Python
- Jupyter Notebook
- SQLite
- Pandas
- Requests

## Pipeline de Dados

O pipeline segue o modelo **ETL**:

1. **Extract**  
   Extração de dados da API pública:
   http://universities.hipolabs.com

2. **Transform**  
   Conversão do JSON retornado pela API em um DataFrame estruturado.

3. **Load**  
   Persistência dos dados em um banco relacional SQLite.

## Estrutura do Projeto
```
universities-api-etl
│
├── universities_api_etl.ipynb
├── universities.db
└── README.md
```


## Objetivo

Este projeto foi desenvolvido como atividade da disciplina **Engenharia de Dados e Bigdata**, com foco em:

- consumo de APIs
- transformação de dados
- modelagem relacional
- persistência de dados