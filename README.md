# 📊 Trader Performance vs Market Sentiment  
### *Internship Assessment – Data Analysis using Hyperliquid Trading Data & Bitcoin Fear–Greed Index*

This project analyzes how **market sentiment** influences **trader performance** by combining:

- **Hyperliquid historical trading data**, and  
- The **Bitcoin Fear & Greed Index**

It uncovers key behavioral patterns such as profitability during Greed/Fear phases, risk-taking tendencies, win-rate variations, and correlations between PnL and sentiment.

---

# 📁 Project Structure



```
Internship_Assessment/
│
├── fear_greed_index.csv       # Sentiment dataset
├── historical_data.csv        # Hyperliquid trading dataset
├── Insights.ipynb             # Main analysis notebook
└── requirements.txt           # Python dependencies
```

---

# 🚀 Getting Started

## 1️⃣ **Clone the Repository**

```bash
git clone https://github.com/ShivangGit123/Internship_Assessment.git
cd Internship_Assessment
```

---

# 🛠️ Installation

Install dependencies using:

```bash
pip install -r requirements.txt
```

Dependencies include:

- pandas  
- numpy  
- matplotlib  
- seaborn  

(Exactly as provided in your `requirements.txt`)

---

# ▶️ Running the Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Then open:

```
Insights.ipynb
```

Run all cells to reproduce:

- Data cleaning  
- Timestamp conversions  
- Dataset merging  
- EDA visualizations  
- Performance metrics  
- Final insights  

---

# 📊 What This Project Does

### ✔️ Cleans and prepares the datasets  
- Converts UNIX → datetime  
- Removes unneeded columns  
- Extracts date for merging  

### ✔️ Merges sentiment with trading performance  
Joining on the **date** column.

### ✔️ Performs complete EDA including:
- Sentiment cycles (Fear → Greed)  
- PnL timeline  
- Avg PnL by sentiment  
- Position size vs sentiment  
- Win-rate analysis  
- Correlation heatmap  

### ✔️ Generates final insights on trader behavior:
- When the trader performs best  
- How sentiment affects risk-taking  
- Which market phases cause losses  
- Statistical relationships between sentiment & PnL  

---

# 🧠 Key Findings

- **Best performance** occurs during **Greed**  
- **Worst performance** occurs during **Extreme Fear**  
- Trader takes **larger positions** when sentiment is high  
- Win-rate improves with increasing sentiment score  
- Strong positive **correlation** between PnL and sentiment  

These patterns clearly show that market psychology significantly affects trading outcomes.

---

# 📦 Files Explained

| File | Description |
|------|-------------|
| `historical_data.csv` | Raw Hyperliquid trading dataset |
| `fear_greed_index.csv` | Bitcoin sentiment index data |
| `Insights.ipynb` | Full analysis notebook |
| `requirements.txt` | Python dependencies |

---

# 🌱 Future Enhancements

- Add volatility metrics (ATR, Std Dev)  
- Build a sentiment-driven trading strategy model  
- Create a Streamlit dashboard  
- Add real-time API for Fear & Greed Index  

---

# ✨ Author

**Shivang Mishra**  
Data Science & Machine Learning Enthusiast  
GitHub: https://github.com/ShivangGit123  

---
