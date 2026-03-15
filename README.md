
# 🧾 Fraud Detection and Risk Analysis
This project provides a data-driven solution for financial fraud detection, using Python, Predictive Analytics, PowerBI to streamline operations and minimize financial losses by identifying high-risk transactions.

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#exploratory-data-analysis-eda">Exploratory Data Analysis (EDA)</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#research-questions--key-findings">Predictive Modeling</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

Developed a solution for financial fraud detection by analyzing financial transaction data using Exploratory Data Analysis (EDA) and predictive modeling to identify fraudulent activity. A Power BI dashboard was also created to visualize key metrics and provide actionable business insights from the findings.

---
<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

Effective fraud detection and risk analysis are critical in the financial sector. This project aims to:
- Quantify financial losses and operational inefficiencies caused by fraud
- Uncover key indicators of fraudulent activity through comprehensive data analysis
- Develop a predictive model to proactively identify high-risk transactions
- Validate the model's business impact by analyzing its precision and recall
- Communicate actionable insights and a data-driven solution to business stakeholders
---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

-This project utilizes a synthetic dataset sourced from Kaggle, tailored for financial fraud detection. 
The dataset includes 21 features that simulate key aspects of transaction details and customer behavior, providing a realistic foundation for modeling and analysis.

---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- SQLite
- Python (Pandas, Nimpy, Matplotlib, Seaborn, Scikit-learn, SciPy)
- Power BI (Interactive Visualizations)
- GitHub

---

<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

- Capped extreme values in Transaction_Amount using winsorization to stabilize analysis
- Identified high outlier concentration via box plot visualization
- Planned conversion of Timestamp, handling of missing values, and removal of duplicates


---
<h2><a class="anchor" id="exploratory-data-analysis-eda"></a>Exploratory Data Analysis (EDA)</h2>

**Initial Data Inspection:**
- Fraud_Label shows strong class imbalance
- Summary stats reveal skewed distributions in Transaction_Amount and Risk_Score
**Univariate Analysis:**
- Histograms show heavy concentration of low-value transactions
- Bar charts highlight dominant categories in Transaction_Type and Device_Type
**Bivariate & Multivariate Insights:**
- Fraudulent transactions skew toward higher Transaction_Amount and Risk_Score
- Transaction_Type distribution varies significantly by Fraud_Label
- Time-based patterns suggest fraud spikes during off-business hours
- Scatter plot shows positive correlation between Risk_Score and Transaction_Amount


---
<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

- Class Imbalance: 32% of transactions are fraudulent → naïve model still 68% accurate
- Transaction Amount: Median fraud = $2,500 vs. $250 non-fraud → 900% higher
- Risk Score: Fraud avg = 0.85 vs. 0.15 non-fraud → 467% increase
- Feature Correlation: Risk_Score & Transaction_Amount correlation = 0.91 → strong predictive link
- Business Impact: Baseline = 1,339 fraud cases/month → reducing even 20% saves hundreds of thousands annually


---
<h2><a class="anchor" id="predictive--modeling"></a>Predictive Modeling </h2>

**Confusion Matrix Breakdown:**
- True Positives: Fraud correctly flagged → direct financial protection
- True Negatives: Legitimate transactions passed → smooth operations
- False Positives: Legitimate flagged as fraud → added manual review workload
- False Negatives: Missed fraud → potential financial exposure
**Classification Metrics:**
- Precision: Most flagged transactions were truly fraudulent → efficient review process
- Recall: Model caught more fraud cases than baseline → stronger fraud prevention
- F1-Score: Balanced metric for comparing overall model performance



---
<h2><a class="anchor" id="predictive--modeling"></a>Predictive Modeling Insights </h2>
Identified key fraud indicators by conducting exploratory data analysis on a financial dataset, revealing that fraudulent transactions have a median value 5-10 times higher than legitimate ones and a dramatically higher average risk score. 
Built a predictive model that demonstrated a 5.8% increase in fraud detection rate over a naive baseline, while maintaining an 88% precision to minimize false positives and reduce unnecessary manual reviews


---
<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

- Total Transactions, Fraud Value, Fraudulent Transactions, False Positives (highlighted as KPI cards)
- Risk Score Distribution (Histogram) → clear separation of fraud at higher scores
- Fraud Over Time (Line Chart) → compares fraud trends against overall volume
- Transaction Amount vs. Risk Score (Scatter Plot) → strong visual correlation between amount and risk
- Fraud by Category (Bar Chart) → breakdown by Transaction_Type, Device_Type, Merchant_Category
- True Positives & True Negatives (Cards) → positioned for quick model performance review

https://github.com/KaltaRawal/fraud-detection-and-risk-analysis-python-powerbi/blob/906cfb1627bcb0b6deb107fbd2267e03175790e0/dashboard.png

---

<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Kalta Rawal**  
📧 Email: kaltarawal52@gmail.com
🔗 [LinkedIn](https://www.linkedin.com/in/kalta-rawal-86547525b/)  
