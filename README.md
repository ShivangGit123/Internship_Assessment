# 📊 Trader Performance vs Market Sentiment  
### *Analyzing Hyperliquid Trading Data with the Bitcoin Fear & Greed Index*

---

## 📌 Overview

Using Python and basic data science libraries, this project:

1. **Cleans and prepares** both datasets  
2. **Converts timestamps** into usable dates  
3. **Merges trade data with sentiment**  
4. Performs **EDA** including:
   - Fear vs Greed cycles  
   - PnL over time  
   - Average PnL by sentiment  
   - Position size vs sentiment  
   - Win rate vs sentiment  
   - Correlation heatmap  
5. Produces **insights on trader behavior** during different sentiment phases  

---

## 📁 Project Structure

```
📦 project-folder
 ┣ 📜 Insights.ipynb
 ┣ 📜 requirements.txt
 ┣ 📊 historical_data.csv
 ┣ 📊 fear_greed_index.csv
 ┗ 📜 README.md
```

---

## 📄 Datasets

### 1. Fear & Greed Index  
Contains:
- `date`  
- `value`  
- `classification`  

### 2. Hyperliquid Execution Data  
Contains:
- `Timestamp`  
- `Execution Price`  
- `Size USD`  
- `Side`  
- `Closed PnL`  

---

## 🧹 Data Preparation

- Converted UNIX timestamps  
- Extracted date column  
- Selected relevant columns  
- Merged datasets  
- Added win-rate flag  
- Cleaned missing values  

---

## 📊 Exploratory Analysis

- Market sentiment timeline  
- Trader PnL over time  
- Average PnL per sentiment  
- Risk appetite (position size vs sentiment)  
- Win rate vs sentiment  
- PnL–Sentiment correlation  

---

## 🧠 Key Findings

- **Best performance** occurs during *Greed*  
- **Worst performance** occurs during *Extreme Fear*  
- Traders take **larger positions** during Greed phases  
- **Win rate is higher** when sentiment is positive  
- Strong **positive correlation** between sentiment value and PnL  

These findings show that market psychology has a measurable effect on trading outcomes.

---

## 🛠 Technologies Used

- Python  
- Pandas  
- Numpy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## ▶️ Running the Project

### 1. Install dependencies
```
pip install -r requirements.txt
```

### 2. Open the notebook
```
jupyter notebook Insights.ipynb
```

### 3. Run all cells

---

## ⭐ Future Enhancements

- Add volatility indicators  
- Build sentiment-driven trading model  
- Deploy as a Streamlit dashboard  
- Integrate real-time sentiment API  

---

## ✨ Author

**Shivang Mishra**  
Data Science & Machine Learning Enthusiast
