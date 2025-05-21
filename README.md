# DETECTION-OF-FRAUD-IN-FINANCIAL


This project demonstrates a complete pipeline for detecting financial fraud using machine learning and visualizing the insights with an interactive Power BI dashboard.

## 📁 Project Structure

- `.ipynb`: Jupyter Notebook containing data preprocessing, exploratory data analysis, model building, and evaluation.
- `.xlsx`: Dataset used for training and evaluation, containing transaction records.
- `.pbix`: Power BI file for visualizing fraud detection metrics and insights.

---

## 🔍 Objectives

- Analyze transaction data for patterns associated with fraud
- Build a machine learning model to detect fraudulent transactions
- Create a business-friendly dashboard for non-technical stakeholders

---

## 📊 Tools & Technologies

- **Python** (with pandas, scikit-learn, matplotlib, seaborn)
- **Jupyter Notebook**
- **Power BI**
- **Excel**

---

## 📌 How to Use

### 1. Run the Jupyter Notebook

```bash
Open `fraud_detection_model.ipynb` in Jupyter Notebook

Load and explore the dataset

Preprocess data: handle missing values, encode categorical variables, normalize features

Train machine learning models (e.g., Logistic Regression, Random Forest, etc.)

Evaluate models using metrics like accuracy, precision, recall, F1-score

Export results (if needed) for use in Power BI

2. Use the Excel Dataset
Ensure financial_transactions.xlsx is placed in the same directory as the notebook

This dataset is also used as the data source for the Power BI dashboard

3. Open the Power BI Dashboard
Open fraud_dashboard.pbix in Power BI Desktop

Refresh the data connection if needed to point to the correct Excel file

Explore visualizations: fraud rate by region, transaction type, time trends, etc.

📈 Machine Learning Models
The notebook includes implementation of multiple models with evaluation:

Logistic Regression

Decision Tree / Random Forest

XGBoost (optional)

Confusion matrix and ROC curve visualizations

📌 Key Insights
Identification of features most associated with fraud

Visualization of high-risk regions or transaction types

Model performance summary with potential for deployment

✅ Requirements
Python Libraries
Install required Python packages with:

bash
Copy
Edit
pip install pandas scikit-learn matplotlib seaborn openpyxl
Power BI
Power BI Desktop (free)

Excel file (financial_transactions.xlsx) as data source

📬 Contact
For questions or suggestions, feel free to reach out.
