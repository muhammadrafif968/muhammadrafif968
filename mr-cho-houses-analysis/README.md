
# 🏠 House Price Analysis & Segmentation – Helping Mr. Cho Make Smarter Property Decisions

This project helps Mr. Cho, a data-savvy homebuyer, make smarter decisions when choosing a house.  
Using an end-to-end data science pipeline, we analyze housing data, predict prices, and segment homes into meaningful groups based on features like size, condition, and renovation history.

---

## ⚙️ Tools & Techniques Used

- Python: `Pandas`, `NumPy`, `Scikit-Learn`, `Seaborn`, `Matplotlib`
- CRISP-DM Framework
- Data cleaning: handling outliers, missing values, duplicates
- Feature engineering: log transformation of skewed price data
- Exploratory Data Analysis (EDA)
- Regression models: Linear Regression, Random Forest
- Model evaluation: MAE, RMSE, R², prediction error analysis
- Clustering: KMeans with Elbow Method
- Dimensionality Reduction: PCA
- Cluster interpretation & visualization

---

## 📊 Key Insights & Results

- ✅ Random Forest outperformed linear models in predicting house prices (better MAE, RMSE).
- 📉 High-priced homes were harder to predict — price volatility is higher in premium properties.
- 🧩 KMeans clustering revealed 4 market segments:
  - Budget classics
  - Spacious premium homes with views
  - Large older homes with big basements
  - Modern mid-sized homes (often newer builds)
- 🔍 PCA projection helped visualize how house features naturally separate into clusters.

---

## 🚀 Why This Project Matters

- Shows my ability to run a full machine learning pipeline from scratch.
- Combines real-world problem framing with exploratory insight and technical modeling.
- Bridges technical results with business value (e.g., helping buyers like Mr. Cho make data-driven decisions).
- Applies both supervised and unsupervised learning with interpretation.

---

## 📂 Project Structure

```
├── data_porto_2.csv          # Raw dataset (used in Google Colab)
├── notebooks/
│   ├── part1_recommendation.ipynb      # Filtering & recommendation logic
│   ├── part2_price_prediction.ipynb    # Modeling & evaluation
│   └── part3_clustering.ipynb          # KMeans, PCA, cluster analysis
├── images/                   # Visuals (EDA, PCA, cluster plots, etc.)
└── README.md                 # Project summary
```

---

## ▶️ How to Use / Run This Project

1. Open the notebooks in [Google Colab](https://colab.research.google.com/)
2. Upload `data_porto_2.csv` when prompted
3. Run the cells step-by-step to follow the analysis flow

---

## ✍️ Author

**Muhammad Rafif**  
Freelance Data Enthusiast / Product Researcher  
📍 Bukittinggi, Indonesia  
📫 Contact: https://www.linkedin.com/in/muhammad-rafif-8a1b20293/
