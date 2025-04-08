# ML_PROJECT- Car Price Predictor
Project Made By Het Patel and Krish Dalsaniya

ML_PROJECT/
├── data/               # Contains datasets used in the project
├── docs/               # Project documentation
├── models/             # Trained machine learning models
├── notebook/           # Jupyter or Colab notebooks
├── src/                # Source code files
├── LICENSE             # License information
├── README.md           # Project overview and details
├── requirements.txt    # List of project dependencies
└── SRC/                # FLASK BACKEND FOR HANDLING FRONTEND DATA


# Car Price Predictor

A machine learning web application that predicts the resale price of a used car based on features like company, model, year, fuel type, and kilometers driven.

---

##  Objective

To build a predictive model that helps users estimate the selling price of used cars using real-world data and a simple, interactive web interface.

---

##  Dataset Used

- **Source**: [Quikr.com](https://www.quikr.com)
- **File**: `quikr_car.csv`
- **Size**: ~8,000 records (after cleaning)
- **Features**: Car name, brand, model, year, fuel type, kilometers driven, price, etc.

###  Preprocessing Steps

- Removed null or invalid entries
- Extracted brand/model from names
- Converted prices and distances to numerical format
- Applied One-Hot Encoding to categorical features

---

## Model Chosen

- **Algorithm**: Linear Regression
- **Why?**
  - Simple and interpretable
  - Good baseline for regression tasks
  - Efficient with structured data

---

##  Performance Metrics

- **R² Score**: ~0.92 on test data
- **Train/Test Split**: 80/20
- **Interpretation**: The model explains about 92% of the price variance

---

##  Installation & Run

###  Requirements

Install dependencies with:
```bash
pip install -r requirements.txt
