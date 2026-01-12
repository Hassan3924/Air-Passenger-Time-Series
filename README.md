# **Air-Passenger-Time-Series ANALYSIS**

Developing a model that can forecast the future of tourism in Germany.

## **About the Dataset**
The dataset is real and taken from https://ec.europa.eu/eurostat/databrowser/view/avia_paocc/default/table?lang=en&category=avia.avia_pa.avia_pao. 

## **Project Overview**

### **Exploratory Data Analysis (EDA) and Preprocessing**
1. **Import Libraries and Load Dataset**
    - Essential libraries are imported, and the dataset is loaded for analysis.

2. **Exploratory Data Analysis (EDA)**
    - **Numerical EDA**: Summary Statistics
        - **Target Variable Analysis**: Insights on the distribution and characteristics of the target variable.
    - **Visual EDA: Data Visualization**: Various visualizations to explore relationships and patterns in the data.
    - 
3. **Data Preprocessing**
    * **Data Cleaning and Reduction:** Steps taken to clean the dataset and reduce dimensionality if necessary.
    * **Handling Missing Data:** Strategies employed to address missing values.
    * **Outlier Detection and Treatment:** Identification and treatment of outliers in the dataset.
    * **Feature Engineering:** Creation of new features to enhance model performance.
    * **Data Scaling and Encoding:** Techniques applied to scale numerical features and encode categorical features.
    * **Time Series Plot:** Techniques applied for Time Series data to under seasonality, trends using decomposing techniques.
      
4. **Model Development**

    * **Baseline Model Evaluation:** Initial evaluation of various models to establish a performance baseline.
      * **Model** Used ARIMA, SARIMAX but ultimately settled with Smoothing technique. 
          
5. **Final Model Evaluation**
    * **Model evaluation:** Evaluating and comparing the performance of the model of base and optimized using MAE, RMSE, MAPE as well as testing with our own prediction vs actual from an accuracy over 90%!
    * **Predictions on the Test Set and Final Evaluation Metrics:** Generating predictions on the test set and calculating final evaluation metrics.
    * **Save the Final Model:** The final model is saved for future predictions and usage.

## **Summary**
This project provides an in-depth exploration of future of tourism in Germany. As we all know Covid took a hit of everything and through meticulous EDA, preprocessing, and modeling, we aim to deliver actionable insights and a robust predictive model. The findings and methodologies presented in this project can serve as a foundation for better understanding the future of tourism in Germany as we see that Germany is slowly backing to the tourism of pre-covid. 
