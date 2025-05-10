Heart Disease Prediction 🫀
This project uses a Logistic Regression model to predict whether a person is likely to have heart disease based on various medical parameters. It includes data preprocessing, model training, evaluation, and a prediction interface for single inputs.

✅ Features
Logistic Regression model
Input scaling using StandardScaler
Handles single patient input for real-time prediction
Warning suppression for clean output
Predicts: “The Person has Heart Disease” or “The Person does not have Heart Disease”

📊 Input Features
Feature	Description
age	Age of the person
sex	Gender (1 = male; 0 = female)
cp	Chest pain type (0–3)
trestbps	Resting blood pressure
chol	Serum cholesterol in mg/dl
fbs	Fasting blood sugar > 120 mg/dl (1/0)
restecg	Resting ECG results (0–2)
thalach	Maximum heart rate achieved
exang	Exercise-induced angina (1/0)
oldpeak	ST depression induced by exercise
slope	Slope of peak exercise ST segment
ca	Number of major vessels (0–3)
thal	Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)

🛠 How to Run
Clone this repo or open the .ipynb in Jupyter/Colab.

Install dependencies:

pip install pandas numpy scikit-learn
Run all cells in the notebook.
