
# California Housing Prices Prediction

A machine learning project to predict median house values in California using the classic California Housing dataset. Achieved **82.38% accuracy** with Random Forest Regressor.

## 📊 Project Overview

This project uses the California Housing Prices dataset to build and evaluate a regression model for predicting median house prices based on features like location, rooms, population, and income.

**Current Model Performance:**  
**R² Score: 0.8238380642630709** (82.38% variance explained)

## 🛠 Tech Stack

- **Language:** Python
- **Notebook:** Jupyter Notebook (house.ipynb)
- **Libraries:** pandas, numpy, scikit-learn, matplotlib/seaborn
- **IDE:** Visual Studio Code
- **Dataset:** Kaggle California Housing Prices

## 📁 Project Structure

```
california-housing-prediction/
│
├── housing.csv              # Dataset (20,640 samples, 10 features)
├── house.ipynb             # Main analysis & ML pipeline
└── README.md              # Project documentation
```

## 🏠 Dataset

**Source:** [California Housing Prices (Kaggle)](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

**Features (10 total):**
- `MedInc`: Median income in block group
- `HouseAge`: Median house age in block
- `AveRooms`: Average number of rooms per household
- `AveBedrms`: Average number of bedrooms per household
- `Population`: Block population
- `AveOccup`: Average number of household members
- `Latitude`, `Longitude`: Block group location
- `ocean_proximity`: Proximity to ocean (categorical)
- `median_house_value`: **Target** (median house value in $100,000s)

**Dataset Size:** 20,640 samples × 10 features

## 🚀 Quick Start

1. **Clone/Download** the repository
2. **Install dependencies:**
   ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
   ```
3. **Open** `house.ipynb` in VS Code or Jupyter
4. **Run all cells** to see the complete pipeline
5. **View results** - R² score of **0.8238** on test set!

## 📈 Model Performance

| Metric | Score |
|--------|-------|
| **R² Score (Test Set)** | **0.8238** |
| Status | ✅ Implemented up to `forest.score(x_test_s, y_test)` |

**Model:** Random Forest Regressor

## 🔄 Workflow Implemented

1. ✅ **Data Loading** - housing.csv
2. ✅ **EDA** - Statistical analysis & visualizations
3. ✅ **Preprocessing** - Handling categorical variables, scaling
4. ✅ **Train-Test Split**
5. ✅ **Random Forest Model Training**
6. ✅ **Model Evaluation** - R² score: **0.8238**

## 📊 Key Results

```
Random Forest R² Score: 0.8238380642630709
```
The model explains **82.38%** of the variance in house prices!

## 🎯 Next Steps (Planned Enhancements)

- [ ] Hyperparameter tuning (GridSearchCV/RandomizedSearchCV)
- [ ] Cross-validation
- [ ] Feature importance analysis & visualization
- [ ] Compare with other models (XGBoost, LightGBM, Neural Networks)
- [ ] Model deployment (Flask/FastAPI)
- [ ] Interactive dashboard (Streamlit/Plotly Dash)

## 📝 Usage

Open `house.ipynb` and run all cells sequentially. The notebook contains:

1. Complete data preprocessing pipeline
2. Exploratory data analysis with visualizations
3. Model training and evaluation
4. Performance metrics and interpretation

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- [California Housing Prices Dataset](https://www.kaggle.com/datasets/camnugent/california-housing-prices) by @camnugent
- Scikit-learn documentation & examples
- [YouTube Tutorial](https://www.youtube.com/watch?v=Wqmtf9SA_kk&t=12s) for initial inspiration

***

**Built with ❤️ by Avani Parab | First-year CSE(AI&ML) Student**

***

