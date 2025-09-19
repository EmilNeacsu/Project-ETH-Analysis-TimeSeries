# 📈 Ethereum Profitability & Volatility Analysis  

## 📌 Project Overview  
This project analyzes the **profitability and volatility of Ethereum (ETH)**, one of the most popular cryptocurrencies worldwide. The research investigates whether Ethereum can be considered a **safe investment** and potentially adopted as a **global digital currency**.  

The analysis covers the period **April 2019 – April 2022**, highlighting the effects of global shocks such as the **COVID-19 pandemic** on Ethereum’s price dynamics.  

---

## 🎯 Objectives  
- Analyze Ethereum’s historical performance (2019–2022)  
- Evaluate **returns and volatility** of ETH  
- Build **time series econometric models** (ARIMA, ARCH, GARCH)  
- Understand the impact of global shocks on crypto markets  
- Assess whether Ethereum is a **stable long-term investment**  

---

## 🛠️ Tools & Technologies  
- **RStudio** – time series modeling and visualization  
- **R Packages**:  
  - `tidyverse`, `ggplot2`, `gt` – data processing & visualization  
  - `forecast`, `tseries`, `urca`, `lmtest`, `nortsTest` – statistical testing  
  - `fGarch`, `FinTS` – ARCH/GARCH volatility models  
- **Excel** – supplementary graphs  
- **Yahoo Finance** – ETH daily price data  

---

## 📊 Methodology  
1. **Data Collection** – Ethereum daily prices (Yahoo Finance)  
2. **Descriptive Statistics** – min, max, mean, quartiles  
3. **Stationarity Testing** – Augmented Dickey-Fuller (ADF)  
4. **Modeling**:  
   - ARIMA(1,0,1) for return series  
   - ARCH models for volatility effects  
   - GARCH(1,1) as final volatility model  
5. **Validation** – Ljung-Box, Shapiro-Wilk, Jarque-Bera, ARCH-LM tests  

---

## 📈 Key Results  
- ETH returns are **stationary**, but volatility is **time-varying**.  
- **COVID-19** (March–April 2020) triggered a strong volatility spike.  
- Another volatility peak occurred in **Summer 2021**, linked to energy consumption debates.  
- Outside of shocks, ETH shows **relative stability**, with long-term upward trends.  
- The **GARCH(1,1) model** best described Ethereum’s volatility clustering and persistence.  

---

## 📸 Example Outputs  
- Ethereum price evolution (2019–2022)  
- Log returns over time  
- ACF/PACF plots for ARIMA identification  
- Conditional variance estimated by GARCH(1,1)  

---

## 📁 Dataset  
👉 [Yahoo Finance – ETH-USD Historical Data](https://finance.yahoo.com/quote/ETH-USD/history?p=ETH-USD)  

---

## 🧑‍💻 Author  
**Emil Neacșu**  
Bachelor’s Thesis – Economic Cybernetics, ASE Bucharest  
🔗 [LinkedIn](https://www.linkedin.com/in/emil-mihai-neacsu-159169209/)  
