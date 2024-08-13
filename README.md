# Hass Avocado Prices Prediction

## **Introduction**
This project aims to analyze, forecast, and predict the prices of Hass avocados using various machine learning models. We performed extensive Exploratory Data Analysis (EDA) and employed multiple regression models to find the best predictors for future avocado prices.

## **Dataset**

The data for this project comes from the Hass Avocado Board and contains information about avocado prices and sales volume in different regions of the United States. The dataset includes both conventional and organic avocados with different Price Look-Up (PLU) codes.

## Contact
- **LinkedIn** : [Henrique Baptista](https://www.linkedin.com/in/henrique-baptista777/)
- **GitHub** : [henriquebap](https://github.com/henriquebap)
- **Email** : [henriquebaptista2003@gmail.com](mailto:henriquebaptista2003@gmail.com)

## **Exploratory Data Analysis (EDA)**

### **Key Insights**

1. **Conventional Avocados**: Generally cheaper with higher sales volume. Consumers likely prefer conventional avocados due to their cost-effectiveness.
2. **Organic Avocados**: Pricier with lower sales volume. The significant price difference suggests cost concerns might drive consumer preferences.
3. **Seasonal Trends**: Sales peaks in February and May 2016, and February 2017 coincide with the lowest prices, indicating seasonal effects on demand.
4. **Regional Sales Dynamics**: Highest sales in the West and California regions, followed by South Central and North East.
5. **PLU and Bag Types**: Avocados with PLU 4046 and 4225 see higher sales and small bags are the most sold.

### **Plots**

1. Average Price Over Time
   
  ![Average Price Over Time](https://github.com/henriquebap/Avocado-Prices-EDA-Model-Traning/blob/main/imgs/Average%20Price%20Type.png)
  
2. Total Volume Over Time
   
  ![Total Volume Over Time](https://github.com/henriquebap/Avocado-Prices-EDA-Model-Traning/blob/main/imgs/total%20Volume%20over%20time.png)

3. Total Bags Over Time
   
  ![Total Bags Over Time](https://github.com/henriquebap/Avocado-Prices-EDA-Model-Traning/blob/main/imgs/total%20bags%20over%20time.png)
  
4. Count of Observations per Region
   
  ![Count of Observations per Region](https://github.com/henriquebap/Avocado-Prices-EDA-Model-Traning/blob/main/imgs/Count%20observation%20per%20Region.png)

5. All date trending Avocado Price
   
  ![All date trending Avocado AvgPrice](https://github.com/henriquebap/Avocado-Prices-EDA-Model-Traning/blob/main/imgs/all%20date%20trend%20prices%20avocados.png)
  
6. Average Price over months
   
  ![Average Price over months](https://github.com/henriquebap/Avocado-Prices-EDA-Model-Traning/blob/main/imgs/trends%20all%20teh%20years%20avocados.png)

7. Average Price over time
   
  ![Average Price over time](https://github.com/henriquebap/Avocado-Prices-EDA-Model-Traning/blob/main/imgs/average%20Price%20Over%20Time.png)

## **Models**

We trained the following regression models:

1. **Linear Regression**
2. **Decision Tree Regressor**
3. **Random Forest Regressor**
4. **XGBoost Regressor**

### **Model Performance**

The Random Forest Regressor outperformed the other models in both predictive accuracy and explanatory power.

| Model | Mean Absolute Error (MAE) | R² Score |
|----------|----------|----------|
| Linear Regression | 0.240946 | 0.392978 | 
| Decision Tree | 0.144929 | 0.690714 | 
| Random Forest | 0.110448 | 0.847877 | 
| XGBoost | 0.116721 | 0.842305 |


### **Results Visualization**

1.**MAE and R² Score Comparison**

![**MAE and R² Score Comparison**:](https://github.com/henriquebap/Avocado-Prices-EDA-Model-Traning/blob/main/imgs/MAe%20and%20R2%20score%20comparison.png)

2. **Random Forest & XGBOOST: Actual vs Predicted Prices:**

![Random Forest & XGBOOST: Actual vs Predicted Prices:](https://github.com/henriquebap/Avocado-Prices-EDA-Model-Traning/blob/main/imgs/RandomForest%20And%20xGboost%20Acutal%20vs%20Predicted%20prices.png)

## **Usage**

### **Prerequisites**

- Python 3.x
- Required libraries: pandas, seaborn, matplotlib, scikit-learn, xgboost

### **Installation**

`pip install pandas seaborn matplotlib scikit-learn xgboost`

### **Running the Project**

1. **Clone the Repository**

`[git clone https://github.com/yourusername/hass-avocado-prices.git](https://github.com/henriquebap/Avocado-Prices-EDA-Model-Traning.git)
cd Notebook/Avocado_Price_Prediction_EDA.ipynb`

2. **Load Dataset**

Place the dataset in the project directory. Ensure it's named appropriately (e.g., **`avocado.csv`**).


### **EDA and Model Training**

The script **`[notebook](https://github.com/henriquebap/Avocado-Prices-EDA-Model-Traning/blob/main/Notebook/Avocado_Price_Prediction_EDA.ipynb)`** performs EDA, trains the models, evaluates them, and generates prediction plots. Ensure your dataset is correctly formatted.

## **Acknowledgments**

- The Hass Avocado Board for providing the dataset.
