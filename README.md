#  Apriori Algorithm for Market Basket Analysis

##  Overview
This project implements the **Apriori algorithm** to discover **frequent itemsets** and generate **association rules** from transactional data.  
Apriori is a foundational data mining technique widely used in **market basket analysis**, **recommendation systems**, and **pattern discovery**.

---

##  Objectives
- Identify frequently occurring item combinations
- Generate association rules using:
  - **Support**
  - **Confidence**
  - **Lift**
- Analyze relationships between items in transactional datasets

---

##  Key Concepts
- Frequent Itemset Mining
- Association Rule Learning
- Support, Confidence, Lift
- Transaction Encoding

---

##  Tech Stack
- **Python**
- **Jupyter Notebook**
- `pandas`
- `numpy`
- `apyori`

---

##  Project Structure
apriori-market-basket-analysis/
│
├── Apriori.ipynb
├── README.md
├── requirements.txt
└── data/

---

##  Workflow
1. Load and preprocess transactional data
2. Convert transactions into one-hot encoded format
3. Apply the **Apriori algorithm**
4. Generate association rules
5. Analyze results using confidence and lift metrics

---

##  Results
- Extracted frequent itemsets based on minimum support threshold
- Generated meaningful association rules
- Identified strong item co-occurrence patterns

---

##  How to Run
```bash
pip install -r requirements.txt
jupyter notebook Apriori.ipynb