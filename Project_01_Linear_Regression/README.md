# 📊 Linear Regression Project  

## 📌 Overview  
This project demonstrates the implementation of a **Linear Regression model** using **Scikit-Learn**.  
The goal is to explore the relationship between features and a target variable while applying **Exploratory Data Analysis (EDA)** and visualizing regression lines with **Seaborn**.

---

## 🛠 Tools & Libraries Used  
- **Pandas**: For data manipulation and analysis  
- **NumPy**: For numerical operations  
- **Matplotlib & Seaborn**: For data visualization and regression line plotting  
- **Scikit-Learn**: For training and evaluating the **Linear Regression** model  

---

## 🔍 Exploratory Data Analysis (EDA)  
Before building the model, we applied **EDA techniques** to understand the dataset:  
✔️ Checked for missing values and handled them if necessary  
✔️ Analyzed basic statistics using `df.describe()`  
✔️ Used **Seaborn's pairplot** to observe relationships between features  
✔️ Plotted correlation heatmaps to identify feature importance  

---

## 📈 Model Implementation  
The **Linear Regression model** was implemented using **Scikit-Learn**:  
1️⃣ Split the dataset into **training (80%)** and **testing (20%)** sets  
2️⃣ Trained the **Linear Regression** model on the training data  
3️⃣ Predicted target values for both train & test sets  
4️⃣ Evaluated the model using **Mean Squared Error (MSE)** and **R² Score**  

---

## 🎨 Data Visualization  
To better understand model performance, we visualized results using **Seaborn**:  
📌 **Scatter plots with regression lines** for each feature  
📌 **Subplots** to compare train and test data points  
📌 **Color-coded points** to differentiate between train (🔵 Blue) and test (🟢 Green) data  

---

## 🚀 How to Use This Project  

### 🔹 Clone the Repository  
To download this project to your local machine, open a terminal and run:  
```sh
git clone https://github.com/Aliha7ish/30-ML-Data.SC-Projects.git

Then navigate to the project folder:

```sh
cd 30-ML-Data.SC-Projects/Project_01_Linear_Regression

### 🔹 Install Dependencies
Ensure you have Python installed, then install the required libraries using:

```sh
pip install -r requirements.txt

### 🔹 Run the Jupyter Notebook
To execute the project and explore the results, run:

```sh
jupyter notebook linear_regression.ipynb
