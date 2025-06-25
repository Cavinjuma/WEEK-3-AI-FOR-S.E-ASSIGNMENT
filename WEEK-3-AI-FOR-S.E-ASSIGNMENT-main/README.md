# 🌸 Iris Flower Classification using Logistic Regression

This project demonstrates a basic machine learning workflow using the **Iris dataset**. The goal is to classify iris flowers into three species: *setosa*, *versicolor*, and *virginica* based on their petal and sepal measurements.

## 📚 Dataset
The Iris dataset is a classic in the field of machine learning. It contains:
- **150 samples**
- **4 features**: sepal length, sepal width, petal length, and petal width
- **3 classes** (flower species): 
  - 0 = Setosa  
  - 1 = Versicolor  
  - 2 = Virginica

## 🧠 Objective
To train a **Logistic Regression** model to accurately classify the species of an iris flower using its physical features.

---

## 🔧 Technologies and Libraries
- Python 🐍
- NumPy
- scikit-learn (sklearn)

---

## 🚀 Steps Performed

1. **Import Libraries**  
   All necessary Python libraries were imported at the top for proper structure and clarity.

2. **Load Dataset**  
   Used `load_iris()` from `sklearn.datasets` to access features and labels.

3. **Split Data**  
   Used `train_test_split()` to divide data into:
   - 60% for training
   - 40% for testing

4. **Model Training**  
   Applied `LogisticRegression(max_iter=1000)` to train the model on training data.

5. **Prediction and Evaluation**  
   The trained model was tested using unseen data and evaluated using `classification_report()`.

---

## 📊 Results

The model achieved **100% accuracy** on the test data with perfect precision, recall, and F1-scores for all three classes.


          precision    recall  f1-score   support

       0       1.00      1.00      1.00        23
       1       1.00      1.00      1.00        19
       2       1.00      1.00      1.00        18

accuracy                           1.00        60



---

## ✅ Ethical Considerations

- Ensure the model is not misused in sensitive or high-risk areas without further testing.
- Always give credit to original dataset creators.
- Make sure data is handled respectfully, especially if working with real human-related data in future projects.

---

## 🛠 Troubleshooting Challenges

- Adjusted `max_iter=1000` to resolve **convergence warning** from Logistic Regression.
- Ensured correct shape of `X_train`, `X_test`, `y_train`, and `y_test`.
- Used `random_state=42` to maintain reproducibility of results.

---


## 👥 Contributors

**Group 61**  
 
1.Joyce Njihia - nyamburanjihia@gmail.com
2.Gospel Arinze - gospelarinzestuff@gmail.com
3.Ling Mukiri - lingmukiri13@gmail.com
4.Juma Calvin - jumacavin28@gmail.com
5.EstherTrizar  - esthertrizar@gmail.com

---

Thank you for reviewing our submission. Kindly check the PDF report for full answers and model output details.


