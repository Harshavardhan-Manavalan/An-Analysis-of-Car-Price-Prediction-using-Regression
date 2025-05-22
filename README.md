# 🚗 Car Price Prediction Using Machine Learning

This project aims to predict the **selling price of used cars** using multiple machine learning regression models. It builds upon the research paper [An Analysis of Car Price Prediction Using Machine Learning](https://doi.org/10.5281/zenodo.15308198), and extends it with additional models and cross-validation techniques.

## 📌 Features

- Trained on a real-world car dataset from [Kaggle](https://www.kaggle.com/datasets/nehalbirla/vehicle-dataset-from-cardekho)
- Multiple regression models implemented and compared
- 5-Fold Cross Validation for reliable evaluation
- Visual analysis using correlation heatmaps and prediction plots

## 📊 Algorithms Used

- Linear Regression  
- Lasso Regression  
- Ridge Regression  
- Multivariate Linear Regression  
- Decision Tree Regressor  
- Random Forest Regressor  
- XGBoost Regressor

## 🧠 Dataset Features

- `Present_Price`  
- `Kms_Driven`  
- `Fuel_Type`  
- `Seller_Type`  
- `Transmission`  
- `Owner`  
- `Car_Age` (calculated from Year)

## 🛠️ Libraries Used

- `pandas`, `numpy`, `matplotlib`, `seaborn`  
- `scikit-learn`  
- `xgboost`

## 🔧 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/car-price-prediction-ml.git
   cd car-price-prediction-ml
````

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the main script:

   ```bash
   python an_analysis_of_car_price_prediction_using_machine_learning.py
   ```

## 📈 Results

* R² scores are calculated for both train and test datasets for all models.
* Visualizations include:

  * Actual vs Predicted plots
  * Comparison of model performances
  * Heatmap of feature correlation

## 📚 Reference

This project is inspired by the research:
**An Analysis of Car Price Prediction Using Machine Learning**
DOI: [10.5281/zenodo.15308198](https://doi.org/10.5281/zenodo.15308198)

## 💡 Future Work

* Deploy the model via a web interface
* Add more features like car location, brand popularity, etc.
* Experiment with deep learning models

## 📬 Contact

For any queries or collaborations, feel free to reach out at:
📧 harshavardhanmanavalan@gmail.com
🔗 LinkedIn Profile - https://www.linkedin.com/in/harshavardhan-manavalan/
