# Exploratory Analysis of Trading Activity on Polymarket

## Project 1 — Which Market Categories Attract the Most Trading Activity?

### 1. Project Overview

Polymarket is a prediction-market platform where users trade contracts based on future events. Markets cover subjects such as cryptocurrency, esports, sports, politics, and other topics.

This project explores transaction activity across different market categories to identify which categories account for the largest share of recorded transactions.

**Main research question:**

> Which market categories have the highest transaction activity in the collected Polymarket dataset?

### 2. Dataset and Scope

- **Platform:** Polymarket
- **Dataset:** Transactions
- **Period:** February 2026 – October 11, 2026
- **Records analyzed:** 882 transactions
- **Categories:** 6
- **Analysis type:** Exploratory Data Analysis (EDA)

Markets were manually assigned to categories. The results describe the collected dataset and should not automatically be generalized to all Polymarket activity.

### 3. Methodology

The analysis involved inspecting the transaction data, assigning records to categories, counting transactions, calculating category percentages, and visualizing the results with a horizontal bar chart.

The main metric is **transaction count**. It measures recorded transaction frequency, not the number of unique traders or the total money traded.

### 4. Results and Visualization

[![Transaction Count by Market Category](images/TransactionCount_chart.png)
](https://github.com/younessaithsaine45-cpu/Polymarket/blob/main/transactions_by_category.png?raw=true)
*Figure 1. Recorded transactions by market category (882 records).*

| Market category | Transactions | Share |
|:--|--:|--:|
| Crypto | 400 | 45.4% |
| Esports | 200 | 22.7% |
| Other | 104 | 11.8% |
| Traditional Sports | 95 | 10.8% |
| Tennis | 64 | 7.3% |
| Weather | 19 | 2.2% |
| **Total** | **882** | **100.0%** |

### 5. Analysis and Interpretation

#### Crypto dominates recorded activity

Crypto leads with 400 transactions, representing 45.4% of the dataset. Its count is twice that of Esports, the second-largest category.

This suggests that cryptocurrency-related markets account for a substantial share of activity in this sample. However, the chart alone cannot explain why this category is more active.

#### Activity is concentrated in two categories

Crypto and Esports together account for 600 transactions, or approximately **68.0%** of all records. The other four categories represent the remaining 32.0%.

This indicates an uneven distribution of transaction activity, with two categories contributing most of the records.

#### Other categories have smaller shares

Other accounts for 104 transactions, followed by Traditional Sports with 95, Tennis with 64, and Weather with 19.

Esports, Traditional Sports, and Tennis together represent 359 transactions, or approximately **40.7%** of the dataset. This comparison depends on grouping these three categories as sports-related activity.

The Other category should be interpreted cautiously because it combines markets that may cover different subjects.

#### Transaction count does not equal financial value

A category with more transactions does not necessarily have more money traded or more unique participants. Many small transactions could outnumber a smaller number of high-value transactions.

Further analysis of transaction sizes, prices, and trader activity would be needed to investigate these differences.

### 6. Key Findings

- **Crypto ranks first**, with 400 transactions (45.4%).
- **Esports ranks second**, with 200 transactions (22.7%).
- Together, they account for approximately **68.0%** of recorded activity.
- **Weather ranks last**, with 19 transactions (2.2%).
- The distribution is concentrated in a few categories, but transaction counts alone cannot explain the reasons behind it.

### 7. Limitations

- **Coverage:** The dataset covers February 2026 through October 11, 2026; its completeness has not necessarily been verified.
- **Manual categorization:** Different classification choices could change the results.
- **Unequal market counts:** Categories may contain different numbers of markets, which could affect their total transaction counts.
- **Repeated activity:** Multiple transactions may come from the same trader.
- **Limited metric:** Transaction counts do not measure total trading value, unique traders, or profitability.

The analysis identifies patterns but cannot establish what causes them.

### 8. Conclusion

In this dataset of 882 transaction records, Crypto and Esports account for approximately 68.0% of activity, while Weather has the lowest transaction count.

The findings suggest that recorded trading activity is concentrated in a small number of categories. Additional metrics are needed to determine whether the same pattern appears in trading value, market participation, or profitability.

### 9. Next Steps

Future analyses will explore:

- Individual markets with the highest transaction counts.
- Transaction price distributions.
- Transaction size distributions.
- Changes in activity over time.
- Comparisons with market characteristics such as liquidity, where suitable data is available.

### 10. Tools and Technologies

Python · Pandas · Matplotlib · Jupyter Notebook · GitHub

---

*Independent exploratory analysis. Conclusions are limited to the collected dataset and the methods used.*
