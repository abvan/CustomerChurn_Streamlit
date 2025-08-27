# 📊 ANN Churn & Salary Prediction  

This project was created as a learning exercise for **Artificial Neural Networks (ANNs)**. It uses the **Churn_Modelling dataset** to explore both **classification** and **regression** tasks, along with a simple **Streamlit app** for customer churn prediction.  

---

## 🚀 Features  

- **Classification Model** – Predict whether a customer will churn.  
- **Regression Model** – Estimate the salary of a customer.  
- **Streamlit App** – Interactive web app (`app.py`) for churn prediction.  
- **Data Preprocessing & Training** – Done in `experiments.ipynb`.  
- **Model Prediction** – Using trained model (`model.h5`) in `prediction.ipynb`.  
- **Pickle Files** – Pre-trained encoders and scalers stored in `pickle_files/`.  

---

## 📂 Project Structure  

```
├── app.py                # Streamlit application for classification
├── experiments.ipynb     # Data preprocessing & model training
├── prediction.ipynb      # Model loading & prediction
├── model.h5              # Saved ANN model
├── pickle_files/         # LabelEncoders, OneHotEncoders, Scalers
└── README.md             # Project documentation
```

---

## ⚙️ Installation & Setup  

1. Clone the repository  
   ```bash
   git clone https://github.com/your-username/ann-churn-salary.git
   cd ann-churn-salary
   ```

2. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Streamlit app  
   ```bash
   streamlit run app.py
   ```

---

## 🧠 How It Works  

1. **Classification (Churn Prediction)**  
   - Uses ANN to classify customers as likely to churn or not.  
   - Preprocessing includes encoding categorical features and scaling numerical ones.  

2. **Regression (Salary Estimation)**  
   - ANN regression model predicts estimated salary.  

3. **Streamlit App**  
   - Provides a simple UI to input customer data.  
   - Loads preprocessing pipelines (from `pickle_files/`) and trained ANN (`model.h5`).  

---

## 📌 Requirements  

- Python 3.8+  
- TensorFlow / Keras  
- scikit-learn  
- Pandas, NumPy  
- Streamlit  

(See `requirements.txt` for full list.)  

---

## 📊 Dataset  

- **Churn_Modelling.csv**  
- Contains customer demographic and account details.  
- Target variable for classification: `Exited` (1 = churn, 0 = no churn).  
- Regression target: `EstimatedSalary`.  

---

## 🎯 Future Improvements  

- Add hyperparameter tuning for ANN models.  
- Deploy Streamlit app on cloud (Streamlit Cloud / Heroku).  
- Add model performance comparison with other ML algorithms.  

---

## 🤝 Contributing  

This is a learning project, but contributions, suggestions, and feedback are welcome!  

---

## 📜 License  

This project is open-source and available under the **MIT License**.  
