# used_car_market_analysis

## 📋 Project Overview
This project performs an Exploratory Data Analysis (EDA) on a dataset of used car listings scraped from Craigslist (2021) across the United States. The goal is to identify pricing patterns and market behavior to generate actionable business insights applicable to platforms like Kavak.

## 🎯 Business Questions
- What factors most influence the price of a used car?
- Which manufacturers command the highest prices vs. the highest sales volume?
- Which vehicle types dominate the market by price and by volume?

## 📊 Dataset
- **Source**: [Craigslist Cars & Trucks Dataset — Kaggle](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data) on June 6th 2026.
- **Size**: 426,880 listings (filtered to 379,910 after price range cleaning)
- **Price range used**: $1,000 — $100,000
- **Year**: 2021

## 🔍 Key Findings
1. **Model year** is the strongest price predictor (correlation: 0.37) — post-2010 vehicles show a clear upward price trend.
2. **Mileage** has a moderate negative correlation with price (-0.20) — higher odometer readings lead to lower prices.
3. **Premium brands** (Ferrari, Aston-Martin, Tesla) lead in average price but are virtually absent in sales volume.
4. **American brands** dominate total sales — Ford leads at ~$1.35B, nearly double Chevrolet's ~$1B.
5. **SUVs** are the volume king ($1.23B total) despite ranking #6 in average price.
6. **Pickup trucks** are the most consistent segment — #1 in average price and #2 in total volume.

## 🛠️ Tech Stack
- Python
- Pandas
- Matplotlib
- Seaborn

## 📁 Project Structure
used-car-market-analysis/

├── README.md

├── main.ipynb

├── requirements.txt

└── vehicles.csv (File not included on the repository, download it from the link and add it to the project folder https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data) 

## ▶️ How to Run Locally
```bash
# Clone the repository
git clone https://github.com/tu-usuario/used-car-market-analysis.git
cd used-car-market-analysis

# Download the .csv file and add it to the project folder

# Create and activate virtual environment
python -m venv venv
.\venv\Scripts\activate  # Windows
source venv/bin/activate  # Mac/Linux

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook main.ipynb
```

## 💼 Business Implication
For a platform like Kavak, the most profitable segment by volume lies in **SUVs and pickup trucks from American brands** (Ford, Chevrolet, RAM, GMC) with **post-2010 model years** and **moderate mileage** — a combination that maximizes both sale price and market demand.

## 👤 Author
Santiago Quintanilla — Mechatronics Engineer | Data Science Student @ TripleTen
[LinkedIn](https://www.linkedin.com/in/santiago-quintanilla-zurita-b5117b103) | [GitHub](https://github.com/borre3205)
