# 📊 Previsão de Séries Temporais - Competição M3 (Série 2049)

Este repositório contém um estudo detalhado sobre a previsão de séries temporais utilizando modelos estatísticos e de aprendizado de máquina. O projeto foi desenvolvido como parte da análise da **Série 2049** da **Competição de Previsão M3**, utilizando o pacote `Mcomp` do R.

---

## 📖 Sobre o Projeto

A análise foi realizada para explorar diferentes abordagens de modelagem preditiva para séries temporais. Os modelos testados incluem:

- **ARIMA** (AutoRegressive Integrated Moving Average)
- **ETS** (Error, Trend, Seasonality)
- **Box-Cox Transformation**
- Comparação entre modelos baseados em **métricas de erro (MAE, AIC, BIC, KPSS, Shapiro-Wilk, Ljung-Box)**

A pesquisa busca determinar a melhor abordagem para previsões precisas, comparando diferentes técnicas e verificando a significância estatística dos resultados.

---

## 🔧 Requisitos

Antes de rodar o projeto, certifique-se de ter os seguintes pacotes instalados no **R**:
```r
install.packages(c("Mcomp", "tseries", "tidyverse", "forecast", "ggplot2"))
```

