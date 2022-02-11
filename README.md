# Nasa-Prognostic-and-Diagnostic-Data-Analysis

# Project 1: Lithium Ion Battery - Preventive Maintenace
 * The project is an extention analysis and modeling from the [notebook](https://www.kaggle.com/rajeevsharma993/battery-health-nasa-dataset) of Rudra from Kaggle. In Rudra notebook, he used LSTM-Deep learning models to predict the time that capacity of the battery reaching threshold. However, computational load is very intensive since this is a very large dataset.
 * This project delivered alternative models including AR models, Machine Learning models with approximate errors compare to the LSTM model. A special feature of this project is the best order of AR models has bean determine by a range of order from 1 to 19. The best order is the number of data point used to predict the next cycle's capacity. The best order is chosen by Akaike Information Criterion (AIC). Machine Learning models are also also performed with comparabel results. A report with clear explaination is delivered.
   1. [Python notebook](https://github.com/ThanhNg1712/Nasa-Prognostic-and-Diagnostic-Data-Analysis/blob/main/Lithium%20Ion%20Battery/battery_health_ar_model_vs_lstm%20(1).ipynb), includes
      1. Data Enginnering: Conduct complete Data Frame from raw, check and clean missing data
      2. Data EDA: Visualizations of features over time, correlationships
      3. LSTM models motivated by Rudra notebook
      4. AR model with best order
      5. Machine Learning model selections and optimizations
  2.[Dataset](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#battery) can be found from Nasa Data Repository
  3.[Report](https://github.com/ThanhNg1712/Nasa-Prognostic-and-Diagnostic-Data-Analysis/blob/main/Lithium%20Ion%20Battery/Report.pdf) with clear explaination and        comparison

# Project 2 : Nava Propulsion Plant
* The project provides models to predict time to failure of Naval propulsion plan for predictive maintenace, includes:
  1.[Python note book](https://github.com/ThanhNg1712/Nasa-Prognostic-and-Diagnostic-Data-Analysis/blob/main/Naval%20Propulsion%20Plan/naval-propulsion-conditionbasemaintence.ipynb), the notebook includes comments and explaiations
    1. Data enginnering: Conducting data frame, checking and cleaning missing data
    2. Data EDA : Data visualizations of features, correlationships, check and drop redundant or constant variables
    3. Model selections: Linear Regression, Random Forest, KNN, Decision Tree, Bagging, XGB Regressor
    4. Reduction dimensions with PCA and opimize performance of the best model: Bagging
  2. [ Dataset](http://archive.ics.uci.edu/ml/datasets/Condition+Based+Maintenance+of+Naval+Propulsion+Plants?ref=datanews.io) on UCI Machine Learning Repository
 
 # Project 3: Nasa Turbofan Degradation - Preventive Maintenance
 * The project aims to optimize the computational load of predictive models using Deep Learning model-LSTM. LSTM is a common model that widely used in predidicting  upcoming failures for preventive maintenance, but computational load is intensive, which is time-consuming. The project applied LSTM model with AR model, the      idea fitting LSTM model with train set, then the concept of AR model is applied to predict future performance on test set.
 *  In particular, only a group of data in test set is used to predict the next data point. In the note book, 10 entries is used to predict eleventh data  and 5 entries is used to predicted sixth data
 *  The project goes with
    1.[Python notebook](https://github.com/ThanhNg1712/Nasa-Prognostic-and-Diagnostic-Data-Analysis/blob/main/Nasa%20Turbofan/nasa-turbofan-predict-rul-using-lstm-and-ar-model.ipynb)
    2.[Dataset](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/#turbofan) can be found on Nasa Data Repository
 
 
