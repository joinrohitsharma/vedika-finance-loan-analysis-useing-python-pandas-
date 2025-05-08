# vedika-finance-loan-analysis-useing-python-pandas-
 complete data analysis project on customer and loan performance data from Vedika Finance. This project includes detailed data cleaning, exploratory data analysis (EDA), segmentation, risk modeling, and customer insights.


 ---

## 🧠 Project Objectives

- Optimize loan performance and collections
- Predict customer default risk
- Enhance customer engagement and segmentation
- Generate actionable insights through data storytelling and visualizations

---

## 📁 Repository Structure
vedika-finance-loan-analysis/
│
├── data/ # Raw and cleaned datasets
├── notebooks/
│ ├── 01_data_cleaning.ipynb # Data cleaning and quality checks
│ ├── 02_eda_visuals.ipynb # Descriptive and visual analysis
│ ├── 03_loan_performance.ipynb # Performance trends and branch-level metrics
│ ├── 04_segmentation.ipynb # Customer segmentation logic
│ ├── 05_risk_model.ipynb # Predictive modeling: defaults
│ └── 06_customer_insights.ipynb# Engagement, loyalty, complaints
├── models/
│ └── loan_default_model.pkl # Trained ML model (Logistic/Tree)
├── reports/
│ └── summary_report.pdf # Final report with graphs and insights
├── README.md
└── requirements.txt # Libraries to install


## 🔧 Data Cleaning & Quality Checks (5 Qs)

1. Missing values in credit bureau scores (CIBIL, Experian, Equifax)?
2. Any customers aged <18 or >100?
3. EMI = 0 but status = "Active"?
4. Duplicate Customer ID or Loan ID?
5. Invalid contact/Aadhar numbers?

---

## 📊 Descriptive Analysis (10 Qs)

- Average loan amount by type
- Interest rate distribution by purpose
- Disbursement value by city/state
- Job titles with highest EMI
- Average CIBIL by age group
- Loan disbursement trend (monthly)
- Education level vs average borrowing
- Defaults with 0 dependents
- EMI vs Loan Tenure
- Loan-to-Income ratio by employment

---

## 📉 Loan Performance Analysis (10 Qs)

- % loans overdue > 30 days
- Top defaulting Loan Officers
- Marital status vs repayment
- EMI performance vs income band
- Industry-wise default rates
- Moratorium impact on defaults
- Insurance vs default
- Dependents vs overdue
- Branches with highest outstanding
- Prepayment behavior analysis

---

## 👥 Segmentation (5 Qs)

- Repayment behavior: 4 segments
- Default by age group
- Employment x Education = Default?
- First-time vs repeat customer loan sizes
- Low loyalty vs communication mode

---

## ⚠️ Risk Assessment (10 Qs)

- Default rate for CIBIL < 600
- Debt-to-Income vs default correlation
- Active loans of defaulters
- Previous defaults vs overdue
- Credit card dues impact on delay
- Default prediction using CIBIL + Income
- Feature importance
- ROC AUC of model
- Confusion matrix
- Top 5 high-risk customers

---

## 💡 Customer Insights & Engagement (10 Qs)

- Best communication modes for repayment
- Complaints vs overdue loans
- Loyalty score vs perfect EMI payers
- Post-disbursement agreement signing?
- Insurance link vs foreclosure rate
- Multi-product customers vs default rate
- Best banks for performance
- Fastest branches (disbursement time)
- Complaint type vs EMI issues
- Fraud-flag vs overdue correlation

---

## 📈 Graph Insights

- EMI default trend – last 12 months
- Loan type vs average interest rate
- Overdue % by branch
- Age group vs default % 
- Employment type vs average CIBIL

---

## 🧠 Tools & Tech

- Python, Pandas, Matplotlib, Seaborn
- Scikit-learn for predictive models
- Jupyter Notebooks
- GitHub & VS Code
- Optional: Streamlit/Power BI (for dashboarding)

---

## 🧪 How to Run

```bash
# Clone the repo
git clone https://github.com/yourusername/vedika-finance-loan-analysis.git
cd vedika-finance-loan-analysis

# Install dependencies
pip install -r requirements.txt

# Launch notebooks
jupyter notebook
