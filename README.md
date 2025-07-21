# Employee Salary Prediction Using Machine Learning

This project uses the **Adult Income Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/adult) to predict whether an employee earns more than \$50K annually.  
It explores various machine learning models, compares their performance, and deploys the best-performing classifier.

---

## 📌 Problem Statement
Organizations often face difficulties in predicting salary brackets due to multiple influencing factors such as education, occupation, age, and working hours.  
This project aims to build a machine learning model that predicts salary categories, enabling data-driven decisions for HR analytics and workforce planning.

---

## ⚙️ Tech Stack
- **Programming Language:** Python 3.x
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn, xgboost
- **Environment:** Jupyter Notebook / Anaconda

---

## 📂 Dataset
- **Source:** [UCI Adult Income Dataset](https://archive.ics.uci.edu/ml/datasets/adult)
- **Files Used:**
  - `adult.data` – Training dataset
  - `adult.test` – Test dataset
- **Target Variable:** `income` (`<=50K` or `>50K`)

---

## 🛠️ Project Workflow
1. **Data Loading:** Import `adult.data` and `adult.test`, merge datasets.
2. **Data Cleaning:** Handle missing values (`?`), remove duplicates, standardize `income` labels.
3. **Exploratory Data Analysis (EDA):** Understand feature distributions and correlations.
4. **Preprocessing:** Encode categorical variables and scale numeric features.
5. **Model Building:** Train Logistic Regression, Random Forest, and XGBoost classifiers.
6. **Evaluation:** Compare models using Accuracy, Precision, Recall, F1-Score, and ROC-AUC.
7. **Deployment:** Select XGBoost as the best model and use it for predictions.

---

## 📊 Results
- **Best Performing Model:** XGBoost  
- **Accuracy:** ~85%  
- **Key Predictors:** Age, education level, hours-per-week, occupation  
- **Visuals:** Confusion matrices, ROC curves, and feature importance plots  

---

## 🔮 Future Enhancements
- Deploy the model as a **web app** for real-time predictions.
- Include **more recent and diverse datasets** for better generalization.
- Explore **deep learning models** and advanced ensembles.


---

## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/employee-salary-prediction.git
2. Navigate to the project folder:
   cd employee-salary-prediction

3.Install dependencies:
pip install -r requirements.txt

4.Open Jupyter Notebook:
  jupyter notebook
  
5.Run Employee Salary Prediction.ipynb.

📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.

👤 Author
Mayank Saini

GitHub: @mayanksaini9

LinkedIn: https://www.linkedin.com/in/mayank-saini-a3b566257/
