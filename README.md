# Projeto Treino 

#### A Base de Dados

A base utilizada foi extraída do Kaggle e contém dados de aparelhos telefônicos de marcas populares como: preço, nome, marca, memória RAM, armazenamento e etc. Todos os telefones desse conjunto de dados continuam sendo fabricados. Não inclui telefones descontinuados.

## Processos Realizados

#### Nível Infra
- O Arquivo tratado final foi salvo no MongoDB atlas

#### Nível PySpark

- Extração para um dataframe;
- Definição do Schema (manipulação das tipagens das colunas);
- Renomeação e tradução de colunas;
- Verificação de inconsistências;
- Verificação de valores duplicados presentes no dataframe;
- Verificação e manipulação de valores nulos presentes no dataframe;
- Realização de consultas utilizando filtros e orderBy;
- Realização de Queries utilizando spark.sql


##### OBSERVAÇÃO: A finalidade deste conjunto de dados é treinamento e prática. Ele nunca poderá ser usado para fins comerciais.