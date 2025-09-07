# Power BI - Financial Investment Insights Dashboard

---

## 🔗 Access the Dashboard
 
* 📄 **Dashboard Report:**
  👉 [Click here to view the dashboard](./Dashboard/)

---

## 1. Background and Overview

This personal project dashboard explores individual investment behaviors, preferences, and objectives. It provides valuable insights into how respondents choose different financial instruments, what factors influence their decisions, and how they monitor their investments.

The purpose of this project is to:

* Understand patterns across demographics, objectives, and investment avenues
* Support better decision-making for investors, consultants, and policymakers

---

## 2. Data Structure Overview

The dataset is stored in a single table `FinanceData` with the following columns:

| Column Name                                                   | Description                             |
| ------------------------------------------------------------- | --------------------------------------- |
| `RespondentID`                                                | Unique identifier of respondents        |
| `Gender`, `Age`                                               | Demographic details                     |
| `Investment_Avenues`                                          | Type of financial instrument considered |
| `Stock_Market`                                                | Participation status (Yes/No)           |
| `Factor`, `Objective`, `Purpose`                              | Drivers behind investment decisions     |
| `Duration`                                                    | Time horizon of investment              |
| `Invest_Monitor`                                              | Monitoring frequency                    |
| `Avenue`, `Savings_Objectives`                                | Additional objectives and categories    |
| `Reason_Equity`, `Reason_Mutual`, `Reason_Bonds`, `Reason_FD` | Reasons for choosing instruments        |
| `Source`                                                      | Source of investment information        |
| `Expect_Midpoint`                                             | Expected return midpoint                |
| `Instrument`, `RankValue`                                     | Ranking of investment instruments       |

### Measures Created

* **Pct\_NonInvestors**: Percentage of respondents not investing
* **Pct\_Investors**: Percentage of respondents investing
* **TopChoiceCount**: Most selected investment instrument count
* **Total\_NonInvestors**: Count of respondents not investing
* **Total\_Investors**: Count of respondents investing

---

## 3. Executive Summary

* **Total Respondents**: 40
* **Percentage of Investors**: 93%
* **Percentage of Non-Investors**: 8%
* **Average Expected Return**: 26%

**Demographics**:

* **By Gender**: Male (62.5%), Female (37.5%)
* **By Age**: Most respondents aged **20–30 years**, with peak representation at **27 years (49 respondents)** and **29 years (35 respondents)**

**Investment Preferences**:

* **By Avenue**: Mutual Funds (45%), Equity (25%), Fixed Deposits (23%), Public Provident Fund (8%)
* **Top Choices**: Fixed Deposits (67%), Equity (17%), Debentures (8%), Government Bonds (8%)

**Instruments Ranking**:

* Best ranked: **PPF (2.03)** and **Mutual Funds (2.55)**
* Lowest ranked: **Gold (5.98)** and **Debentures (5.75)**

---

## 4. Insight Deep Dive

### a. **Investment Preferences**

* Respondents show the highest trust in **Mutual Funds (45%)** and **Fixed Deposits (67% top choice)**, suggesting a preference for **moderate risk with steady returns**.
* Equity market is popular (25%) but selected as a top choice by fewer respondents (17%), indicating **perceived higher risk**.

### b. **Reasons Behind Investments**

* **Equity**: 75% seek capital appreciation.
* **Mutual Funds**: 60% expect better returns, with 32.5% valuing diversification.
* **Bonds**: 65% value assured returns, positioning them as a **safe asset class**.
* **Fixed Deposits**: 47.5% consider them risk-free, making them highly attractive for **conservative investors**.

### c. **Objectives & Purposes**

* **Primary Objectives**: Capital appreciation (65%) dominates, followed by growth (27.5%).
* **Sources of Information**: Consultants (40%) are most trusted, followed by newspapers/magazines (35%), TV (15%), and internet (10%).
* **Savings Objectives**: Focused on **retirement (168)**, followed by healthcare (91) and education (21).
* **Purposes**: Wealth creation (224) far outweighs savings for future (42) or returns (14).

### d. **Behavior & Monitoring**

* **Monitoring Frequency**: Majority monitor **monthly (203)**, while a smaller group checks daily (28) or weekly (49).
* **Factors in Decision Making**: 62.5% consider **returns** as the top factor, followed by risk (35%) and locking period (2.5%).

### e. **Stock Market Participation**

Respondents participating in the stock market have **245 investment avenues**, while non-participants have only 14–21. This suggests a **stronger diversification behavior** among market participants.