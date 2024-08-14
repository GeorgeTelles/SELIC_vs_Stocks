<div>
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_clara.png" alt="logo clara" width="300" style="display: inline-block; vertical-align: top; margin-right: 10px;">
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_dark.png" alt="logo dark" width="300" style="display: inline-block; vertical-align: top;">
</div>

# Comparação de Rentabilidade: SELIC vs. Ativos de Renda Variável

Este projeto em Python visa comparar a rentabilidade da taxa SELIC com a rentabilidade de alguns ativos de renda variável (ações) no mercado financeiro. Utilizando as bibliotecas `pandas`, `matplotlib`, `seaborn` e `yfinance`, o projeto analisa a variação percentual dos preços das ações e da SELIC ao longo do tempo. 

## Objetivo

O objetivo é comparar o desempenho da SELIC com o desempenho de ativos de renda variável, como ações, para entender como a rentabilidade desses ativos se relaciona com a taxa de juros básica da economia.

## Bibliotecas Utilizadas

- **pandas**: Para manipulação e análise de dados.
- **matplotlib**: Para criação de gráficos e visualizações.
- **seaborn**: Para estilização e aprimoramento das visualizações.
- **yfinance**: Para coleta de dados financeiros das ações.

## Etapas do Projeto

1. **Extração de Dados da SELIC**
   - Obtém-se os dados da taxa SELIC do Banco Central do Brasil através da sua API.
   - Ajusta-se os dados para a taxa percentual.

2. **Coleta de Dados das Ações**
   - Dados históricos mensais de três ativos (ITUB4, EMBR3, VALE3) são baixados usando `yfinance`.
   - Calcula-se a rentabilidade mensal de cada ativo com base nas variações percentuais dos preços ajustados.

3. **Preparação dos Dados**
   - Ajusta-se e transforma-se os dados para calcular o acumulado das rentabilidades.
   - O ajuste considera o crescimento acumulado dos preços ao longo do tempo.

4. **Visualização dos Dados**
   - **Gráfico de Linha**: Compara as rentabilidades acumuladas da SELIC e dos ativos de renda variável.
   - **Mapa de Calor**: Exibe a correlação entre os retornos dos ativos e a SELIC.

5. **Análise de Correlação**
   - Calcula-se e exibe-se a correlação entre os retornos dos ativos e a SELIC para identificar possíveis padrões ou relações.

## Resultados Esperados

- Visualizações que mostram a comparação da rentabilidade acumulada da SELIC com a dos ativos de renda variável.
- Análise da correlação entre a rentabilidade dos ativos e a SELIC para entender a relação entre eles.

  ![](https://github.com/GeorgeTelles/SELIC_vs_Stocks/blob/dd51275d4c7df2ea83d967b119cd31fac96801e3/plot.png)
