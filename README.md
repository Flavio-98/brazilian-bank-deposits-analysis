# Análise dos Determinantes dos Depósitos Bancários no Brasil (2022-2024)

![Python](https://img.shields.io/badge/Python-3.x-blue?style=flat&logo=python)
![Status](https://img.shields.io/badge/Status-Concluído-green)

## 📋 Sobre o Projeto

Análise do comportamento dos depósitos bancários brasileiros entre 2022 e 2024 utilizando dados do Banco Central do Brasil e variáveis macroeconômicas como PIB, Selic, IPCA e Desemprego.

O objetivo é identificar quais fatores econômicos possuem maior influência sobre a formação de depósitos no sistema financeiro nacional por meio de técnicas de econometria e análise de dados.

## 🎯 Objetivo

Responder à questão: **Como explicar o comportamento dos depósitos totais utilizando PIB, Taxa de Juros (Selic), Inflação (IPCA) e Desemprego?**

Para isso, foi aplicada uma **Regressão Linear Múltiplas (OLS - Ordinary Least Squares)**.

## 📊 Metodologia e Ferramentas

O projeto foi desenvolvido em **Python**, seguindo as etapas:

1.  **ETL (Extração e Tratamento):** Limpeza de dados brutos do Banco Central (conversão de datas e formatos numéricos brasileiros).
2.  **Engenharia de Atributos:** Criação da variável agregada de "Depósitos Totais".
3.  **Análise Estatística:** Matriz de correlação e modelagem OLS.
4.  **Visualização:** Comparação gráfica entre os dados reais e os estimados pelo modelo.

**Bibliotecas utilizadas:**
* `pandas`: Manipulação de dados.
* `statsmodels`: Modelagem estatística e regressão.
* `matplotlib`: Visualização de dados.

## 📈 Principais Resultados

O modelo final apresentou um **R² (Coeficiente de Determinação) de 95,9%**, indicando um altíssimo poder explicativo.

| Variável | Impacto nos Depósitos | Interpretação |
| :--- | :---: | :--- |
| **PIB** | 🟢 Positivo | O crescimento da atividade econômica impulsiona o volume de depósitos. |
| **Desemprego** | 🔴 Negativo | A melhora no mercado de trabalho favorece a formação de poupança bancária. |
| **Taxa Selic** | 🔴 Negativo | Juros altos incentivam a migração de recursos para outros investimentos (efeito substituição), reduzindo os depósitos bancários tradicionais. |
| **IPCA (Inflação)** | ⚪ Neutro | Não apresentou significância estatística relevante no modelo ajustado. |

### Visualização: Real vs Estimado

<img width="1012" height="548" alt="grafico_final" src="https://github.com/user-attachments/assets/632180d0-5db7-44a6-95aa-1df15f4c9139" />

*(O modelo matemático (linha vermelha) segue de perto os dados observados (linha azul), validando a robustez da análise.)*

## 🚀 Como Executar

1. Clone este repositório:
```bash
git clone [https://github.com/Flavio-98/Analise_Depositos_Bancarios_Brasil_2022-2024.git](https://github.com/Flavio-98/Analise_Depositos_Bancarios_Brasil_2022-2024.git)
