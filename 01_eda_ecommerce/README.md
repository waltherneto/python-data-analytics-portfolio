# Exploratory Data Analysis — E-commerce Sales

## 📌 Objective
Analyze e-commerce transactional data to understand revenue trends, product performance, and geographic concentration, and to highlight data-quality issues that affect reporting.

## 📊 Dataset
- Source: Online Retail Dataset
- Type: Transactional e-commerce data
- Typical fields: invoices, product descriptions, quantities, prices, customers, and countries

## 🛠️ Tools Used
- Python (pandas, numpy)
- matplotlib / seaborn

## 🔍 Key Questions
- What is the total revenue in the dataset (after cleaning)?
- How does revenue evolve over time (monthly)?
- Which products generate the most revenue? Is revenue concentrated or long-tail?
- Which countries generate the most revenue? Is there geographic concentration?
- What data quality issues exist (missing values, invalid transactions, duplicates)?

## ✅ Key Findings (Summary)
- Revenue shows strong growth through 2011, with clear peaks; the final month appears lower, consistent with partial-period data.
- Product revenue is long-tail: the **top 10 products contribute ~10%** of total revenue.
- Geographic revenue is highly concentrated in the **United Kingdom** (top-market dependency).

## 📁 Project Structure
- `analysis.ipynb`: main analysis notebook
- `data/`: raw dataset file(s)

## ▶️ How to Run
1. Create and activate a virtual environment
2. Install requirements: `pip install pandas numpy matplotlib seaborn jupyter`
3. Open and run `analysis.ipynb`

## 📌 Notes
- Some items (e.g., **POSTAGE**, **Manual**) may represent non-product revenue and can be analyzed separately in production settings.