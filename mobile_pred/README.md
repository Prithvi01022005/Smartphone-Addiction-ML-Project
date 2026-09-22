\# Smartphone Addiction Prediction System



\## 📌 Project Overview



The Smartphone Addiction Prediction System is a Machine Learning project that analyzes smartphone usage patterns and predicts whether a user is likely to be addicted to smartphone usage.



The project uses a \*\*Random Forest Classifier\*\* to learn patterns from smartphone usage data and classify users based on their usage behavior.



\## 🎯 Objective



The main objective of this project is to use smartphone usage-related features such as screen time, social media usage, gaming time, sleep hours, notifications, and app usage to predict smartphone addiction.



\## 🤖 Machine Learning Algorithm



\### Random Forest Classifier



Random Forest is an ensemble Machine Learning algorithm that combines multiple Decision Trees to make a prediction.



In this project, the Random Forest model is trained using smartphone usage features and the target variable `addicted\_label`.



\## 📊 Dataset



The dataset contains \*\*7,500 records\*\* of smartphone usage data.



\### Input Features



\* Age

\* Daily screen time

\* Social media hours

\* Gaming hours

\* Work/study hours

\* Sleep hours

\* Notifications per day

\* App opens per day

\* Weekend screen time



\### Target



\* `addicted\_label`



The target represents the predicted smartphone addiction classification.



\## 📈 Model Evaluation



The Random Forest model was evaluated using:



\* Accuracy

\* Confusion Matrix

\* Predicted vs. Actual values



The model achieved approximately \*\*92.9% accuracy\*\* on the test dataset.



The dataset was divided into:



\* Training data: 6,000 records

\* Testing data: 1,500 records



\## 🛠️ Technologies Used



\* Python

\* Pandas

\* NumPy

\* Matplotlib

\* Seaborn

\* Scikit-learn

\* Jupyter Notebook



\## 📁 Project Files



```text

Smartphone-Addiction-ML-Project/

│

├── Smartphone\_Addiction\_Random\_Forest.ipynb

├── Smartphone\_Usage\_And\_Addiction\_Analysis\_7500\_Rows.csv

└── README.md

```



\## ▶️ How to Run



1\. Clone or download this repository.

2\. Open `Smartphone\_Addiction\_Random\_Forest.ipynb` using Jupyter Notebook or VS Code.

3\. Install the required Python libraries.

4\. Make sure the dataset CSV file is in the same folder as the notebook.

5\. Run the notebook cells in order.



\## 👨‍💻 Project Focus



This project demonstrates the basic Machine Learning workflow:



\*\*Data Loading → Data Exploration → Data Preprocessing → Train-Test Split → Random Forest Training → Prediction → Model Evaluation\*\*



\## 📌 Note



This project is developed for academic and learning purposes to demonstrate the application of Machine Learning to smartphone usage data.



