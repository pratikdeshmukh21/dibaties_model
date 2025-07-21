# 🩺 Diabetes Risk Prediction Using Logistic Regression

This project implements a diabetes risk prediction model using **Logistic Regression**, trained on a custom dataset with 500 rows and 9 carefully selected, user-friendly health features. The goal is to provide a **simple, interpretable, and accurate tool** to estimate the likelihood that a user may be at risk of diabetes.

## 📊 Dataset

The dataset (`synthetic_diabetes_dataset.csv`) contains **500 rows × 9 columns** with the following fields:

| Feature Name              | Description                                      |
|---------------------------|--------------------------------------------------|
| age                       | Age range (e.g. `20-30`, `40-50`)                |
| sex                       | Gender (`Male`, `Female`)                        |
| family_history            | Family history of diabetes (`Yes`/`No`)          |
| blood_pressure_status     | One of `Normal`, `Prehypertension`, `Hypertension` |
| history_high_blood_sugar  | History of high blood sugar (`Yes`/`No`)         |
| physical_activity         | Activity level (`Low`, `Moderate`, `High`)       |
| smoking_status            | Smoking history (`Never`, `Former`, `Current`)   |
| diabetes                  | Target column (`1` = diabetic, `0` = non-diabetic)|

## 🧠 Model

- **Model Type:** Logistic Regression
- **Preprocessing:** One-Hot Encoding for categorical features
- **Performance:**  
  - Accuracy: **94%**  
  - Class-balanced dataset  
  - Evaluated using `train_test_split` and classification report

## ✅ How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/pratikdeshmukh21/dibaties_model.git
cd diabetes-logistic-model
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Notebook
Open `diabetes_model.ipynb` in Jupyter or Google Colab to explore the code, training pipeline, and evaluation metrics.

### 4. Save
to save the model u can use jolib ar pkl as u wish 
and then use the model 

## 📌 Key Highlights

- Fully interpretable model using real-world health questions
- Accessible input fields—no lab tests required to make predictions
- Pipeline-ready for integration into Streamlit or web apps

## 📣 Call for Contributions

Want to improve the model? Add more features? Deploy it via Flask or Streamlit?  
Feel free to fork and contribute 🤝

## 🧑‍💻 Author

**Pratik Deshmukh**  
Data Science & ML Enthusiast

## 📜 License

This project is licensed under the [MIT License](LICENSE).

Let me know if you want me to generate the `requirements.txt`, Flask/Streamlit starter template, or a pre-made badge layout!
