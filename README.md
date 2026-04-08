# Mental Health in Tech Workplace: Exploratory Data Analysis

## 📌 Project Overview
This project performs a deep-dive Exploratory Data Analysis (EDA) on the "Mental Health in Tech Survey" dataset. As the tech industry faces rising burnout and high-pressure environments, this study aims to quantify the prevalence of mental health issues and identify the corporate barriers that prevent employees from seeking help.

## 🎯 Business Objectives
* **Identify Predictors:** Determine which personal and professional factors (like family history or company size) lead to seeking treatment.
* **Bridge the Awareness Gap:** Analyze employee awareness of workplace benefits.
* **Improve Retention:** Provide data-driven insights to help companies reduce work interference and employee attrition.
* **Stigma Reduction:** Highlight the gap between physical and mental health support in the corporate world.

## 🛠️ Technical Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook / Google Colab

## 🧼 Data Wrangling & Production-Grade Logic
To ensure the analysis is "Deployment Ready," a robust data cleaning pipeline was implemented:
* **Age Normalization:** Handled extreme outliers (e.g., negative values) using median imputation within a realistic range (18–75).
* **Gender Standardization:** Used custom mapping logic to collapse 40+ unique string inputs into three clean categories: **Male, Female, and Other/Non-binary**.
* **Null Imputation:** Strategically filled missing values in `self_employed` and `work_interfere` to preserve data integrity.
* **Exception Handling:** Wrapped cleaning logic in `try-except` blocks for production robustness.

## 📊 Key Insights (UBM Rule)
Following the **Univariate, Bivariate, and Multivariate** rule, 15 charts were generated:
1.  **High Prevalence:** Nearly 50% of the tech workforce has sought treatment.
2.  **Strongest Predictor:** Family history is the #1 driver for seeking professional help.
3.  **The Privacy Gap:** Employees are significantly more likely to seek help if **Anonymity** is explicitly guaranteed.
4.  **Awareness Issue:** A massive "Communication Gap" exists where employees are "Unsure" about the benefits their companies already provide.

## 💡 Strategic Recommendations
* **Institutionalize Anonymity:** Move from vague privacy promises to guaranteed third-party anonymity.
* **Managerial Training:** Train direct supervisors to be the first line of support, as they are the most trusted point of contact according to the data.
* **Normalization:** Treat mental health leave with the same administrative ease as physical medical leave to reduce long-term burnout.

## 🚀 How to Run
1. Clone this repository: `git clone https://github.com/YOUR_USERNAME/Mental-Health-Tech-EDA.git`
2. Install dependencies: `pip install pandas numpy matplotlib seaborn`
3. Run the Jupyter Notebook: `jupyter notebook Sample_EDA_Submission_Template.ipynb`

## 👨‍💻 Author
**Kalash Shah** *Aspiring Data Scientist | Electronics & Telecommunication Engineer*
