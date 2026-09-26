# Atividade Spark - Análise de dados de COVID no Brasil

Este repositório contém uma atividade prática de processamento e análise de dados com Apache Spark, utilizando um conjunto de dados de casos de COVID-19 no Brasil.

## Objetivo

A atividade tem como finalidade explorar o dataset para responder uma série de perguntas analíticas sobre:

- quantidade de casos positivos;
- perfil dos pacientes;
- sintomas mais frequentes;
- distribuição por sexo, idade e município;
- evolução temporal dos casos;
- taxa de óbito por faixa etária;
- análise de municípios e estados do Paraná;
- dias da semana com maior volume de testes e casos positivos.

## Dataset

O conjunto de dados utilizado é referente a pacientes que realizaram exames de COVID-19 no Brasil até março de 2020.

Características do dataset:

- aproximadamente 1,6 GB;
- cerca de 4,4 milhões de instâncias;
- campos como data de notificação, data do teste, resultado do teste, sexo, idade, município, estado, sintomas, evolução do caso e outras informações clínicas.

## Tecnologias utilizadas

- Python
- PySpark
- Google Colab
- gdown para download do arquivo

## Estrutura da atividade

O notebook principal, [AtividadeSpark_colab.ipynb](AtividadeSpark_colab.ipynb), foi desenvolvido para:

1. instalar e configurar o PySpark;
2. baixar o dataset;
3. carregar os dados em um RDD;
4. realizar filtros, agregações e transformações;
5. responder as consultas solicitadas.

## Informações solicitadas

As análises pedidas incluem:

1. quantidade de pacientes positivos para COVID;
2. quantidade de mulheres positivas;
3. quantidade por sexo e resultado do teste;
4. sintomas mais comuns em casos positivos;
5. sintomas mais comuns em casos não positivos;
6. casos positivos no Paraná;
7. município do Paraná com maior número de óbitos;
8. número de municípios paranaenses com casos positivos;
9. número de municípios paranaenses sem casos positivos;
10. estado com maior taxa de falecimento entre mulheres;
11. menor idade de mulher positiva;
12. maior idade de mulher positiva;
13. casos positivos por dia;
14. casos positivos por semana;
15. quantidade de óbitos por idade;
16. taxa de óbito por idade;
17. idade média das mulheres positivas;
18. município do Paraná com maior número de mulheres positivas;
19. dia da semana com mais testes realizados;
20. dia da semana com mais pacientes positivos;
21. município com mais de 500 testes e maior taxa de testes não positivos para COVID.

## Como executar

1. Abra o notebook em ambiente compatível com Colab ou Jupyter.
2. Execute as células na ordem apresentada.
3. Aguarde a instalação das dependências.
4. Faça o download do dataset.
5. Rode as transformações em Spark e visualize os resultados.

## Observações

- A atividade foi pensada para praticar processamento distribuído com Spark sobre um volume grande de dados.
- O objetivo principal é aplicar filtros, agrupamentos e contagens para extrair conhecimento a partir de dados reais.
- Os resultados podem ser usados como base para análise exploratória e relatórios de ciência de dados.

## Repositório

- Notebook principal: [AtividadeSpark_colab.ipynb](AtividadeSpark_colab.ipynb)
- Documentação desta atividade: [README.md](README.md)
