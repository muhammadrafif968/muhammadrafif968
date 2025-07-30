# 🏠 House Price Analysis & Segmentation – Helping Mr. Cho Make Smarter Property Decisions

This project helps Mr. Cho, a data-savvy homebuyer, make smarter decisions when choosing a house.  
Using an end-to-end data science pipeline, we analyze housing data, predict prices, and segment homes into meaningful groups based on features like size, condition, and renovation history.

---

## ⚙️ Tools & Techniques Used

- **Python**: `Pandas`, `NumPy`, `Scikit-Learn`, `Seaborn`, `Matplotlib`
- **CRISP-DM Framework**
- **Data Cleaning**: handling outliers, missing values, duplicates
- **Feature Engineering**: log transformation of skewed price data
- **Exploratory Data Analysis (EDA)**
- **Regression Models**: Linear Regression, Random Forest
- **Model Evaluation**: MAE, RMSE, R², prediction error analysis
- **Clustering**: KMeans with Elbow Method
- **Dimensionality Reduction**: PCA
- **Interactive Dashboard**: Microsoft Power BI (Free version)

---

## 📊 Key Insights & Results

- ✅ Random Forest outperformed linear models in predicting house prices (better MAE, RMSE).
- 📉 High-priced homes were harder to predict — price volatility is higher in premium properties.
- 🧩 KMeans clustering revealed 4 market segments with distinct patterns.
- 🧠 Log-transformed target improved model performance & interpretability.
- 📈 Interactive dashboard allows users to simulate tax/discount impact on house prices.

---

## 📊 Power BI Dashboard (Interactive Showcase)

We built a Power BI dashboard to visualize housing trends and simulate buyer scenarios.  
Included visuals:

- **House Price Trends** by year built and era
- **Property Distribution** by condition, size, and city
- **Simulation Tool** using What-If Parameters (Tax, Discount)
- **Insightful Cards & Filters** for interactivity

> 🔗 **[Download the dashboard (PDF)](https://yourlink.com)**  
> *(Or request interactive file upon contact)*

---

## 📂 Project Structure

├── data_porto_2.csv # Original dataset
├── data_cleaned.csv # Cleaned dataset after preprocessing
├── notebooks/
│ ├── part1_recommendation.ipynb # Filtering & recommendation logic
│ ├── part2_price_prediction.ipynb # Modeling, feature selection, tuning
├── powerbi_dashboard/
│ ├── mr_cho_dashboard.pbix # Final Power BI file (optional)
│ └── exported_dashboard.pdf # Static version of dashboard
├── images/ # Visuals (EDA, PCA, cluster plots, etc.)
└── README.md # Project summary



---

## ▶️ How to Use This Project

1. Clone or download this repo
2. Open the `.ipynb` files via Google Colab or Jupyter
3. Upload `data_cleaned.csv` when prompted
4. Run all cells step-by-step to explore EDA, modeling, and clustering
5. Open `exported_dashboard.pdf` for summarized insights, or open `.pbix` with Power BI Desktop

---

## 💡 Example Use Cases

- 🧠 Understand housing trends over time
- 🔍 Segment properties by quality, condition, and renovation history
- 💰 Simulate price impact based on custom tax & discount inputs
- 📊 Empower buyers or business teams to explore property decisions interactively

---

## ✍️ Author

**Muhammad Rafif**  
Data & Product Enthusiast  
📍 Bukittinggi, Indonesia  
📫 Contact: [LinkedIn](https://www.linkedin.com/in/muhammad-rafif-8a1b20293/)

---

> Made with 💻 Python + 🧠 ML + 📊 Power BI
