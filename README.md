# Comparação das Metodologias TDD e BDD: Análise de Bugs Detectados nas Diferentes Fases do Projeto

Este projeto foi desenvolvido como parte da disciplina **C318 - Fundamentos de Machine Learning** no curso de Engenharia da Computação no Instituto Nacional de Telecomunicações (Inatel). O objetivo do projeto é realizar uma análise comparativa das metodologias **Test-Driven Development (TDD)** e **Behavior-Driven Development (BDD)**, avaliando a detecção de bugs em diferentes fases do desenvolvimento de um projeto computacional.

---

## 🗂️ Estrutura do Projeto

- **notebook/**
  - Contém o Jupyter Notebook com os experimentos e análises.
- **data/**
  - Conjuntos de dados (dataset) utilizados nos experimentos.
- **README.md**
  - Este arquivo.

---

## 🎯 Objetivos do Projeto

1. Realizar uma análise comparativa entre TDD e BDD, considerando os seguintes aspectos:
   - Quantidade de bugs detectados.
   - Fase do projeto em que os bugs foram encontrados.
   - Qualidade e abrangência dos testes implementados.
2. Avaliar os impactos de cada metodologia na produtividade e na qualidade do código desenvolvido.

---

## 📖 Etapas do Desenvolvimento

### 1. Contextualização do Projeto
Definimos como foco a comparação entre TDD e BDD para entender quais metodologias são mais eficazes em termos de detecção de bugs e alinhamento com os requisitos de negócio.

### 2. Pesquisa e Enquadramento do Problema
Formulamos as seguintes perguntas de negócio:
- Qual metodologia detecta mais bugs em fases iniciais do projeto?
- Existe diferença na quantidade total de bugs detectados entre TDD e BDD?

O problema foi enquadrado como uma **análise exploratória de dados**, uma vez que nosso objetivo é compreender os padrões de detecção de bugs.

### 3. Coleta de Dados
Os dados foram coletados a partir de logs gerados durante o desenvolvimento de um projeto exemplo, aplicando ambas as metodologias (TDD e BDD) em paralelo.

### 4. Desenvolvimento Computacional
Implementamos scripts em Python para análise dos logs e geração de métricas como:
- Tempo médio para correção de bugs.
- Quantidade de bugs por fase do projeto.
- Taxa de sucesso dos testes implementados.

### 5. Geração de Resultados
Os resultados foram visualizados utilizando gráficos e relatórios gerados no Jupyter Notebook. As métricas-chave foram apresentadas de forma clara e objetiva.

---

## 🚀 Resultados Obtidos

- **Quantidade de Bugs Detectados:**
  - TDD apresentou maior eficácia em fases iniciais.
  - BDD detectou mais bugs relacionados a requisitos de negócio.
- **Tempo de Correção:**
  - Projetos com BDD apresentaram maior eficiência na correção devido à clareza dos cenários.

Os resultados detalhados estão disponíveis no notebook em `notebook/TDDvsBDD.ipynb`.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Python 3.9
- **Bibliotecas:** pandas, matplotlib, pytest, behave
- **Ferramentas:** Jupyter Notebook, Git, VS Code

---

## ✍️ Autores

- Amanda Silva Guimarães
- Manuela Gripp Silva
- Maria Luiza Silva Raimundo
- Matheus Henrique Braga Julidori

---

## 📋 Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/MatheusJulidori/C318-NP2.git

2. Instale as dependências:
   ```bash
   pip install -r requirements.txt

3. Execute os notebooks ou scripts
   ```bash
   jupyter notebook notebook/TDDvsBDD.ipynb
