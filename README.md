# Análise dos Determinantes dos Depósitos Bancários no Brasil (2022-2024)

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Status](https://img.shields.io/badge/Status-Concluído-green)

## 📋 Sobre o Projeto

Análise do comportamento dos depósitos bancários brasileiros entre 2022 e 2024 utilizando dados do Banco Central do Brasil e variáveis macroeconômicas como PIB, Selic, IPCA e Desemprego.

O objetivo é identificar quais fatores econômicos possuem maior influência sobre a formação de depósitos no sistema financeiro nacional por meio de técnicas de econometria e análise de dados.

## 🎯 Problema de Negócio
Pergunta de pesquisa:

Como fatores macroeconômicos influenciam o comportamento dos depósitos bancários no Brasil?

A compreensão dessa relação auxilia instituições financeiras e analistas econômicos a entender movimentos de liquidez, poupança e comportamento dos agentes econômicos.

## 📂 Dados Utilizados

• Depósitos Bancários – Banco Central do Brasil
• Taxa Selic – Banco Central do Brasil
• PIB – IBGE
• IPCA – IBGE
• Taxa de Desemprego – PNAD Contínua

## 💻 Tecnologias

- Python
- Pandas
- Statsmodels
- Matplotlib
- Jupyter Notebook

## 📊 Metodologia e Ferramentas

1. ETL e tratamento dos dados.
2. Construção da variável Depósitos Totais.
3. Análise exploratória.
4. Matriz de correlação.
5. Regressão Linear Múltipla (OLS).
6. Avaliação do ajuste do modelo.

## 📈 Principais Resultados

R² = 95,9%

Principais achados:

• PIB apresentou impacto positivo nos depósitos bancários.
• Selic apresentou impacto negativo.
• Desemprego apresentou impacto negativo.
• IPCA não apresentou significância estatística relevante.

### Visualização: Real vs Estimado

<img width="1012" height="548" alt="grafico_final" src="https://github.com/user-attachments/assets/632180d0-5db7-44a6-95aa-1df15f4c9139" />

*(O modelo matemático (linha vermelha) segue de perto os dados observados (linha azul), validando a robustez da análise.)*
