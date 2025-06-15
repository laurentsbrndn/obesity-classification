# Comparative Analysis of Machine Learning Algorithms for Obesity Classification

This project presents a comparative analysis of three machine learning algorithms—**K-Nearest Neighbors (KNN)**, **Random Forest (RF)**, and **XGBoost**—to predict obesity levels based on various personal and lifestyle features.

## 🎯 Objective

The main goal of this project is to evaluate the performance of different machine learning models in classifying individuals into one of seven obesity categories:

- Insufficient_Weight  
- Normal_Weight  
- Overweight_Level_I  
- Overweight_Level_II  
- Obesity_Type_I  
- Obesity_Type_II  
- Obesity_Type_III  

## 🔍 Methodology

Each of the three algorithms was tested under the following configurations:

1. **Default configurations**
2. **Grid Search** hyperparameter tuning
3. **Randomized Search** hyperparameter tuning

This results in a total of **nine trained models**. The performance of each model was evaluated using standard metrics such as accuracy, precision, recall, and F1-score.

## ⚙️ Features Used

The dataset includes a variety of features related to personal, behavioral, and lifestyle attributes, such as:

- Gender
- Age
- Height
- Weight
- Family history of overweight
- Frequent consumption of high caloric food
- Frequency of vegetable consumption
- Number of main meals
- Consumption of food between meals
- Smoking status
- Daily water consumption  
- Self-calories consumption monitoring
- Physical activity frequency
- Time using technology devices
- Frequency of alcohol consumption
- Mode of transportation

## 📊 Tools & Technologies

- **Python**  
- **Scikit-learn**  
- **XGBoost**  
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**  
- **Jupyter Notebook** for experimentation

## 📈 Results

The analysis highlights how algorithm selection and hyperparameter tuning can significantly impact model performance. In general:

- **XGBoost** showed consistently strong results across all configurations.
- **Random Forest** was also highly effective, particularly after tuning.
- **KNN** benefited greatly from hyperparameter optimization.

## 📝 Conclusion

This study demonstrates that both the choice of algorithm and the optimization strategy play a crucial role in achieving accurate predictions. Hyperparameter tuning methods such as Grid Search and Randomized Search can substantially improve model performance, especially for algorithms like KNN.