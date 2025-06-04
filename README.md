
# 📊 Sales Prediction Using Python

This project focuses on building a **Sales Prediction Model** using a **Linear Regression** approach in Python. The dataset (`advertising.csv`) contains advertising budgets across three media channels — **TV**, **Radio**, and **Newspaper** — along with the resulting **Sales**. The goal is to predict sales based on how much a company spends on these advertising platforms.

---

## 🧠 Project Objective

To analyze how advertising budgets influence sales and to predict future sales using machine learning techniques. This can help businesses make informed decisions about where to allocate their marketing budgets.

---

## 📁 Dataset Used

**File:** `advertising.csv`
**Location:** `C:\Users\ASUS\Downloads\advertising.csv`

**Columns:**

* `TV` – Budget spent on TV ads
* `Radio` – Budget spent on radio ads
* `Newspaper` – Budget spent on newspaper ads
* `Sales` – Generated sales revenue

---

## 🔧 Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn (LinearRegression)

---

## 🧪 Steps Performed

1. **Import Libraries** – Imported all essential libraries for data analysis and model building.
2. **Load Dataset** – Loaded the `advertising.csv` file using pandas.
3. **Data Preprocessing** – Checked for null values and performed basic data exploration.
4. **Data Visualization** – Plotted heatmaps and scatter plots to understand relationships.
5. **Model Training** – Built and trained a Linear Regression model.
6. **Model Evaluation** – Evaluated the model using MSE, RMSE, and R² Score.
7. **Prediction & Plotting** – Compared actual vs predicted sales visually.

---

## 📈 Model Evaluation

* **Mean Squared Error (MSE)**
* **Root Mean Squared Error (RMSE)**
* **R² Score (Accuracy)**

These metrics were used to determine how well the model predicts sales based on advertising budgets.

---

## 📊 Results

* The model showed a strong correlation between advertising spending and sales.
* TV and Radio investments showed higher impact on sales than Newspaper.
* R² Score indicates how well future samples are likely to be predicted.

---

## 🚀 Future Scope

* Use polynomial or ridge regression for better accuracy.
* Integrate more features like digital ads, influencer marketing, etc.
* Build a dashboard to interactively predict sales based on input budget.

---

## 🏁 Conclusion

This project successfully demonstrates the use of Linear Regression for a real-world business problem — **Sales Forecasting**. It highlights the importance of data-driven decisions in marketing strategies.

