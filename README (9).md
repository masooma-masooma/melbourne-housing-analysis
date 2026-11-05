# Melbourne Housing: EDA, Statistics and Gradient Descent

Exploratory data analysis of the **Melbourne Housing Snapshot** (13,580 property sales) and a **linear regression trained with gradient descent written from scratch**.

## 🎯 What this project does

### `eda_and_gradient_descent.ipynb`
- **Data loading** with `kagglehub`
- **Feature engineering:** year sold and age of the property
- **Missing values:** compares `SimpleImputer` with a manual approach that fills gaps with the median per suburb or region
- **EDA:** correlation heatmaps, scatter plots and regression plots for price against land size, year built and property age, plus analysis by council area (number of houses, highest mean prices)
- **Gradient descent from scratch:** fits `price = m × bedrooms + c` for one suburb and studies how the learning rate affects convergence

### `distributions_and_clt.ipynb`
- Continuous uniform and normal distributions
- A demonstration of the **Central Limit Theorem**

## 🔍 Key findings
- Land size is almost **uncorrelated** with price (r ≈ 0.04)
- Year built has a **weak negative** correlation with price (r ≈ −0.25): older houses tend to sell for more in Melbourne

## 🛠️ Tech Stack
Python · pandas · NumPy · SciPy · scikit-learn · Matplotlib · Seaborn · Plotly

## 🚀 How to Run
```bash
pip install -r requirements.txt
jupyter notebook eda_and_gradient_descent.ipynb
```
The dataset downloads automatically from Kaggle ([dansbecker/melbourne-housing-snapshot](https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot)).

## 👤 Author
Masooma, MSc Applied AI, Year 1
