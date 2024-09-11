# Projeto ETL com Jupyter

Este projeto demonstra diferentes abordagens para o processo de ETL (Extração, Transformação e Carga) utilizando Jupyter Notebooks. O objetivo é fornecer uma base para entender e implementar processos de ETL em projetos de ciência de dados.

## Estrutura do Projeto

- `notebooks/`: Contém os notebooks Jupyter com exemplos de ETL.
- `data/`: Diretório para armazenar conjuntos de dados utilizados nos exemplos.
- `scripts/`: Scripts auxiliares para funções de ETL.


## Tecnologias Utilizadas

- Python
- Pandas
- Schedule
- SQLAlchemy
- Jupyter Notebook

## Metodologias de ETL

Neste projeto, exploramos diferentes metodologias para implementar processos de ETL:

1. **ETL Tradicional**: Extração de dados de fontes, transformação em um formato desejado e carregamento em um banco de dados.
2. **ELT (Extração, Carga e Transformação)**: Extração de dados e carregamento direto em um data warehouse, seguido pela transformação dos dados.
3. **ETL em Tempo Real**: Utilizando a biblioteca schedule para rodar em um loop infinitoo sempre atualizando o processo de ETL.


