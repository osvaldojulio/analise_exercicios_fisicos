# Análise de Exercicíos Físicos

Este projecto descreve três tipos diferentes de actividades: Caminhada, Corrida e Yoga

### Coleta de dados e estruturas de tabela
Os dados necessários foram coletados e estruturados em arquivos Excel. 
Os dados do exercício foram organizados como uma tabela de fatos e as datas e atividades 
foram organizadas como tabelas de dimensão para filtrar os dados.

### Cálculos
Os cálculos a seguir foram criados nos relatórios do Power BI usando DAX (Expressões de Análise de Dados). 
Para diminuir a extensão da codificação, a reutilização de medidas (ramificação de medida) foi enfatizada.

*Média de Etapas – Esta é uma função AVERAGE simples em torno da coluna Steps:

*Total de Etapas – Esta é uma função SOMA simples em torno da coluna Etapas:

*Corrida % do Total – Aqui estamos usando duas medidas de antes para encontrar a % de etapas que foram feitas executando:

*Caminhada % do Total – Aqui estamos usando duas medidas de antes para encontrar a % de passos que foram feitos caminhando

## Capa
![Captura de ecrã 2022-10-19 13:12:04](https://user-images.githubusercontent.com/56509130/196688560-9b81a0c1-721b-4600-b2bd-5d730e79795f.png)


## Overview
![Captura de ecrã 2022-10-19 13:12:34](https://user-images.githubusercontent.com/56509130/196689241-c5f4f6ff-0d59-4f2f-8798-0f53ed6ce230.png)


