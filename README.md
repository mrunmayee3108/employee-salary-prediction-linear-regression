# 📈 Employee Salary Prediction using Linear Regression

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" width="45"/>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="45"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/8/84/Matplotlib_icon.svg" width="45"/>
  <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" width="45"/>
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" width="45"/>
</p>


## 📌 Project Overview

This project implements a **Machine Learning model using Linear Regression** to predict **employee salaries** based on features such as experience, education level, and job-related attributes.

The goal is to understand how different factors influence salary and build a **predictive model** that estimates salary with reasonable accuracy.


## 🎯 Objectives

- Perform data cleaning and preprocessing
- Explore relationships between features and salary
- Build a **Linear Regression model**
- Evaluate model performance using regression metrics
- Visualize predictions and regression trends
- Understand real-world application of supervised learning


## 🧰 Tech Stack

| Category | Tools |
|--------|------|
| Programming | Python |
| Data Handling | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Environment | Jupyter Notebook |


## 📂 Dataset Description

The dataset contains **employee-related information** used to predict salary, including:

- `experience_years`
- `education_level`
- `job_role`
- `age`
- `salary`

> 💡 The dataset is structured for **supervised regression**, where `salary` is the target variable.


## 🧹 Data Preprocessing

Data preprocessing was performed using **Pandas and NumPy** to prepare the dataset for modeling.

### ✔ Steps Performed
- Checked and handled missing values
- Removed duplicate records
- Encoded categorical variables
- Feature scaling (if required)
- Split data into **training and testing sets**

This ensured clean, consistent input for the regression model.


## 📊 Exploratory Data Analysis (EDA)

EDA was conducted to understand feature relationships and salary patterns.

### 🔍 Key Insights
- Salary increases with experience
- Certain job roles show higher average salaries
- Clear linear trends between numerical features and salary
- Presence of outliers affecting regression performance

Visualizations such as:
- Scatter plots
- Correlation heatmaps
- Regression lines  
were used to support analysis.


## 🤖 Machine Learning Model

### 📌 Algorithm Used
- **Linear Regression**

### 🔧 Model Workflow
1. Feature selection
2. Train-test split
3. Model training using `sklearn.linear_model`
4. Salary prediction on test data
5. Performance evaluation


## 📈 Model Evaluation

The model was evaluated using standard regression metrics:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R² Score**

These metrics helped assess how well the model predicts salaries compared to actual values.


## 🚀 Results

- The model successfully learned salary trends
- Predictions closely follow actual salary values
- Linear Regression proved effective for this dataset
- Visual comparison between **actual vs predicted salary** shows good alignment


## 🔮 Future Enhancements

- Add Polynomial Regression for non-linear trends
- Include more features (skills, company size, location)
- Hyperparameter tuning
- Deploy model using **Streamlit**
- Compare with other regression models (Ridge, Lasso)


## ⚙️ How to Run This Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/mrunmayee3108/employee-salary-prediction-linear-regression.git
cd employee-salary-prediction-linear-regression
````


### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```


### 3️⃣ Run the Notebook

```bash
jupyter notebook
```

Open the notebook and run all cells to:

* Preprocess data
* Train the model
* Visualize results

## 👥 Contributing

Pull requests are welcome.
Feel free to fork the repo and improve the model or analysis.


## 📄 License

MIT License.

## 🙏 Acknowledgments

* Dataset source (Kaggle / Open Source)
* Scikit-learn documentation


## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!

**Author:** Mrunmayee Sachin Potdar


