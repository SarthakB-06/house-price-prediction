# 🏠 House Price Prediction

An industry-ready machine learning project to predict house prices using the Ames Housing Dataset.

## 📊 Project Overview

This project demonstrates end-to-end machine learning workflow including:
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Multiple ML Models (Linear Regression, Random Forest, XGBoost)
- Model Evaluation & Comparison
- RESTful API for predictions
- Production-ready code structure

## 🎯 Dataset

**Ames Housing Dataset** - Contains 79 features describing residential homes in Ames, Iowa.
- Source: [Kaggle - House Prices Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- Target Variable: Sale Price
- Features: 79 (including lot size, quality ratings, year built, etc.)

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- pip

### Installation

1. Clone the repository:
```bash
git clone https://github.com/SarthakB-06/house-price-prediction.git
cd house-price-prediction
```

2. Create virtual environment:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:
```bash
pip install -r requirements.txt
```

4. Download the dataset:
- Visit [Kaggle Competition Page](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
- Download `train.csv` and `test.csv`
- Place in `data/raw/` directory

## 📁 Project Structure

```
house-price-prediction/
├── data/                  # Data directory
├── notebooks/             # Jupyter notebooks for EDA & experimentation
├── src/                   # Source code
├── models/                # Trained models
├── api/                   # API code
├── requirements.txt       # Dependencies
└── README.md             # Project documentation
```

## 🔄 Development Status

- [x] Project setup
- [ ] Exploratory Data Analysis
- [ ] Data preprocessing
- [ ] Feature engineering
- [ ] Model training
- [ ] Model evaluation
- [ ] API development
- [ ] Documentation
- [ ] Deployment

## 📈 Models to Implement

1. Linear Regression (Baseline)
2. Ridge/Lasso Regression
3. Random Forest Regressor
4. Gradient Boosting (XGBoost)
5. Ensemble Methods

## 🤝 Contributing

This is a personal learning project, but suggestions are welcome!

## 📄 License

MIT License

## 👨‍💻 Author

**Sarthak** - [GitHub](https://github.com/SarthakB-06)

---

*Built with ❤️ as an industry-ready ML portfolio project*