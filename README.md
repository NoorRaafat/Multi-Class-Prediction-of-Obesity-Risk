## :pushpin: Obesity Classification Project
<br>

 This project aims to classify obesity levels based on various attributes using machine learning techniques.
 The dataset contains 17 attributes, and the records are labeled with the class variable NObesity (Obesity Level),
 which includes categories such as Insufficient Weight, Normal Weight, Overweight Level I, Overweight Level II, Obesity Type I, Obesity Type II, and Obesity Type III. 
 The goal is to build a classifier that can accurately predict the obesity level of individuals based on their attributes.

 ###### The dataset used for this project can be found <a href="https://www.kaggle.com/competitions/playground-series-s4e2/data">Here</a>.

### 📝 Techniques Used
<br>

The following machine learning techniques were employed for classification:

. Logistic Regression

. Decision Trees

. Random Forest

. XGBoost

. LGBMClassifer

The main machine learning technique employed for classification is XGBoost due to its good performance.

### 🧠 Results
<br>

The LGBMClassifer model achieved an accuracy of 91% on the test dataset. 
The confusion matrix and classification report are provided to evaluate the model's performance metrics such as precision, recall, and F1-score for each class.

### ♣️ Usage

<br>

.Prepare the Dataset: Obtain the dataset and load it into your environment.

.Data Preprocessing: Preprocess the dataset by encoding categorical variables and scaling numerical features as necessary.

.Model Training: Train the XGBoost model using the prepared dataset. You can experiment with other machine learning techniques mentioned above.

.Model Evaluation: Evaluate the performance of the XGBoost model using metrics such as accuracy, precision, recall, and F1-score. Compare the results to assess the model's effectiveness in classifying obesity levels.

### Predictions: Utilize the trained XGBoost model to make predictions on new or unseen data. Assess its performance based on the achieved accuracy.

### 🙋 References
<br>
.Dataset

.XGBoost Documentation

.LGBMClassifer Documentation

<br>

##### 🤝 Feel free to explore the notebooks and scripts provided in this repository for detailed implementation and analysis.
