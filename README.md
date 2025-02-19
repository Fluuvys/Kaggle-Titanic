# 🚢 Titanic Survival Prediction using Logistic Regression

## 📌 Overview
This project is a Kaggle competition entry for predicting the survival of passengers on the Titanic using logistic regression. The goal is to classify passengers as survivors or non-survivors based on features such as age, sex, passenger class, and more.

## 📊 Dataset
The dataset used in this project comes from the Titanic - Machine Learning from Disaster competition on Kaggle.
- **📂 Train dataset**: Used to train the model
- **📂 Test dataset**: Used to make predictions for submission
- **🔍 Features include**: 
  - 🆔 PassengerId
  - 🎟️ Pclass (Ticket class)
  - 🏷️ Name
  - 👨‍🦰 Sex
  - 🎂 Age
  - 👨‍👩‍👧‍👦 SibSp (Number of siblings/spouses aboard)
  - 👨‍👩‍👧‍👦 Parch (Number of parents/children aboard)
  - 🎫 Ticket
  - 💰 Fare
  - 🏠 Cabin
  - 🚢 Embarked (Port of Embarkation)

## 💻 Installation & Requirements (Check code)
Ensure you have Python installed along with the necessary dependencies:
```sh
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 🛠️ Approach
1. **🔧 Data Preprocessing**:
   - Handling missing values
   - Encoding categorical variables
   - Feature scaling and selection
   
2. **🤖 Model Training**:
   - Used logistic regression for binary classification
   - Evaluated performance using accuracy score
   
3. **📈 Prediction & Submission**:
   - Applied the trained model on test data
   - Generated a CSV file for submission

## 📊 Evaluation Metrics
- ✅ Accuracy

## 🎯 Results
The logistic regression model achieved an accuracy of **81%** on the validation set.

## 🚀 Future Improvements
- Try different feature engineering techniques
- Experiment with other machine learning models (Random Forest, SVM, Neural Networks)
- Tune hyperparameters for better performance

## 🙌 Acknowledgments
This project is inspired by the Titanic Machine Learning from Disaster challenge on Kaggle. Special thanks to the Kaggle community for valuable discussions and datasets.

## 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.
