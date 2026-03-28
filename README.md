# 📊 Trader Performance vs Market Sentiment Analysis

## 🚀 Key Result

Traders demonstrate higher profitability during **Greed phases**, while **Fear phases** are associated with increased volatility and risk-averse behavior.

---

## 🎯 Objective

The goal of this project is to analyze how market sentiment (Fear vs Greed) influences trader behavior and performance using real trading data from Hyperliquid.

---

## 📁 Datasets

1. **Bitcoin Market Sentiment (Fear/Greed Index)**

   * Columns: Date, Classification

2. **Historical Trader Data (Hyperliquid)**

   * Columns include: Account, Size, Side, Closed PnL, Timestamp, etc.

---

## 🛠️ Tools & Technologies

* Python 🐍
* Pandas & NumPy
* Matplotlib & Seaborn
* Jupyter Notebook (VS Code)

---

## 📂 Project Structure

Trader-Sentiment-Analysis/
│
├── analysis.ipynb
├── README.md
├── data/
│   ├── fear_greed_index.csv
│   ├── historical_data.csv

---

## 🧹 Data Preparation

* Cleaned column names for consistency
* Converted timestamps into datetime format
* Created a common `date` column
* Merged sentiment and trading datasets
* Handled missing values and checked duplicates

---

## ⚙️ Feature Engineering

Created key metrics:

* Daily PnL per trader
* Win/Loss indicator
* Win rate
* Trade frequency
* Average trade size
* Trade size segmentation (High vs Low)
* Long/Short ratio

---

## 📊 Analysis

### 🔹 Sentiment vs Performance

* Compared average PnL and win rate across Fear and Greed conditions

### 🔹 Behavioral Analysis

* Trade size variations across sentiment
* Trade frequency changes
* Buy vs Sell distribution

### 🔹 Trader Segmentation

* Frequent vs Infrequent traders
* High vs Low trade size traders
* Winners vs Losers

---

## 🔥 Key Insights

* Traders perform better during **Greed phases**, achieving higher average PnL
* **Fear phases** result in more volatile and inconsistent trading outcomes
* Traders reduce position sizes during Fear, indicating cautious behavior
* Market sentiment has a stronger influence on performance than trade direction alone

---

## 💡 Strategy Recommendations

* **During Fear conditions:**
  Reduce trade size and avoid aggressive positions to manage risk

* **During Greed conditions:**
  Increase participation while maintaining disciplined risk management

---

## ▶️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/trader-sentiment-analysis.git
   ```

2. Open the project in VS Code

3. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn
   ```

4. Run the notebook:

   ```
   analysis.ipynb
   ```

---

## 🏁 Conclusion

Market sentiment plays a critical role in shaping trader behavior and performance.
Understanding these patterns enables better decision-making and improved risk management strategies.

---


