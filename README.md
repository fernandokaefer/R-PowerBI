# Projeto: Análise de Anomalias com R e Power BI

## Descrição do Projeto

Este projeto foi desenvolvido para realizar a detecção de anomalias em um conjunto de dados utilizando a linguagem R. A técnica de Machine Learning usada foi o *Isolation Forest*, aplicada tanto em dados históricos quanto em novos dados, permitindo identificar pontos fora do padrão e visualizá-los graficamente. 

Após o tratamento dos dados e a criação do modelo preditivo, os resultados foram exportados e integrados ao *Power BI*, onde foi desenvolvido um dashboard interativo para facilitar a análise das anomalias detectadas.

## Etapas do Projeto

1. *Configuração do Ambiente*:
   - O projeto utiliza pacotes como tidyverse, dplyr, solitude, ggplot2, e readr para manipulação e visualização dos dados.
   - Foram carregados e processados dados históricos em um arquivo CSV, seguidos pelo treino de um modelo de Machine Learning.

2. *Detecção de Anomalias*:
   - O modelo foi treinado usando o algoritmo *Isolation Forest, que atribui um **anomaly score* a cada transação.
   - Transações com pontuação acima de 0.62 foram marcadas como anomalias.
   - Foram criadas visualizações com gráficos de dispersão e um *box plot* para comparar as transações normais e anômalas.

3. *Integração com Power BI*:
   - Os resultados foram exportados para uma nova planilha em CSV.
   - O arquivo foi então importado no Power BI, onde foi construído um dashboard para analisar visualmente as anomalias, facilitando a tomada de decisões.

## Tecnologias Utilizadas
- *Linguagem*: R
- *Bibliotecas*: tidyverse, dplyr, solitude, ggplot2, readr
- *Técnicas de Machine Learning*: Isolation Forest
- *Ferramentas de Visualização*: Power BI

## Resultados

Os resultados do modelo permitiram a visualização clara de transações normais e anômalas, com gráficos customizados em R e representações visuais no dashboard do Power BI, proporcionando insights sobre os comportamentos fora do padrão nos dados analisados.
