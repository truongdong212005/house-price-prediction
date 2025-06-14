
# House Price Prediction

This project uses a machine learning regression model to predict house prices based on various property features. The model is trained using a dataset that includes multiple factors such as number of bedrooms, bathrooms, square footage, location, and more.

---

## 🧠 Problem Definition

The goal is to identify which features have the greatest impact on house prices and to predict the price of a house based on its known attributes.

### 🔢 Input Features

- Bedrooms
- Bathrooms
- Living area size (`sqft_living`)
- Lot size (`sqft_lot`)
- Number of floors
- Waterfront presence
- View rating
- House condition
- Design/build quality (`grade`)
- Above-ground area (`sqft_above`)
- Basement area (`sqft_basement`)
- Year built (`yr_built`)
- Year renovated (`yr_renovated`)
- Zipcode
- Latitude & longitude (`lat`, `long`)
- Average living area of 15 nearest houses (`sqft_living15`)
- Average lot size of 15 nearest houses (`sqft_lot15`)

### 🎯 Target Output

- **House Price** (`price`)

This is a **regression** problem where the goal is to predict a continuous numeric value.

---

## 📚 Project Overview

The notebook includes:

- Data preprocessing and feature selection
- Data visualization for correlation analysis
- Model training using regression techniques (e.g., Linear Regression, Decision Tree, etc.)
- Model evaluation using metrics like RMSE or R²
- Prediction on sample test data

---

## 🛠️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/truongdongto/house-price-prediction.git
cd house-price-prediction
```

### 2. Run the Notebook

Launch Jupyter and open the notebook:

```bash
jupyter notebook house-price-prediction.ipynb
```

---

## 📊 Model Evaluation

After training, the model is evaluated using standard regression metrics to determine its performance on unseen data. The notebook provides visualizations and explanations for these metrics.

---

## 📁 Files

```
house-price-prediction/
│
├── house-price-prediction.ipynb    # Main notebook
├── house_pricing.csv               # Dataset for training
└── README.md                       # Project documentation
```

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙏 Acknowledgements

- Dataset and inspiration from housing market prediction tasks
- Tools used: `pandas`, `scikit-learn`, `matplotlib`, `seaborn`, `numpy`
