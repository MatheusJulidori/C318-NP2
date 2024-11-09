# Análise de Desempenho de Projetos de Software com Machine Learning

## Visão Geral

Este projeto visa analisar o desempenho de projetos de software a partir de um conjunto de dados contendo informações detalhadas sobre projetos anteriores. O objetivo principal é avaliar o desempenho de cada projeto com base em métricas-chave, identificar padrões entre as linguagens de programação e metodologias utilizadas, e fornecer insights para otimizar futuros projetos de software.

## Objetivo do Projeto

1. **Avaliar Desempenho**: Calcular o desempenho dos projetos utilizando duas variáveis concretas:
   - **FunctionalSize**: O tamanho funcional do projeto, que reflete a complexidade e o escopo do trabalho.
   - **ProjectElapsedTime**: O tempo de execução do projeto, uma métrica direta de eficiência.

2. **Correlação entre Tamanho e Tempo**: Através da correlação entre o tamanho do projeto (FunctionalSize) e o tempo de execução (ProjectElapsedTime), é possível quantificar o desempenho do projeto. Projetos que alcançam um tempo de execução menor para um tamanho funcional maior são considerados de desempenho mais eficiente.

3. **Agrupamento e Padrões**: A partir dos dados, será realizada uma análise para identificar quais linguagens de programação, tipos de documentação e plataformas de desenvolvimento estão associadas a projetos de maior eficiência. Essa análise permitirá detectar quais combinações de tecnologias e metodologias tendem a resultar em um melhor desempenho.

## Metodologia

### Análise de Desempenho

Para quantificar o desempenho dos projetos, serão utilizados modelos de regressão supervisionados para prever o tempo de execução de novos projetos com base nas características observadas. Além disso, a correlação entre `FunctionalSize` e `ProjectElapsedTime` será medida para fornecer um índice de desempenho.

### Machine Learning

O modelo principal será um **Random Forest Regressor**, que permite capturar relações complexas entre variáveis sem a necessidade de suposições lineares. O modelo será treinado para prever o tempo de execução do projeto com base nas características do projeto, tais como:

- Linguagem de programação primária.
- Tipo de documentação.
- Plataforma de desenvolvimento.
- Técnica de gestão de desenvolvimento (e.g., Agile, Waterfall).

### Agrupamento de Dados

Além da regressão, será feito um agrupamento de dados para identificar padrões de desempenho. Projetos com características semelhantes (linguagens, plataforma, técnicas de documentação) serão agrupados e comparados quanto ao desempenho, permitindo insights sobre quais combinações geram melhores resultados.

## Benefícios do Projeto

1. **Melhoria Contínua de Projetos**: As empresas podem utilizar esses insights para escolher metodologias, linguagens e ferramentas que tendem a resultar em maior eficiência.
2. **Planejamento de Recursos**: Com a previsão de tempo de execução baseada em características de novos projetos, é possível alocar recursos de maneira mais precisa, aumentando a probabilidade de cumprimento de prazos e qualidade.
3. **Redução de Custos e Atrasos**: Identificar as combinações de fatores que maximizam o desempenho pode reduzir retrabalhos, custos extras e atrasos no desenvolvimento de software.
