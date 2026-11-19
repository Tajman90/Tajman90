## Hi there, I'm Tajudeen Omotosho 

<div align="center">
  <!--  You can customize the typing text in the "lines=" section of the URL below -->
  <!--  For an ampersand (&), use &amp; (e.g., Analytics+%26+Optimization) -->
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2E9EF7&center=true&vCenter=true&width=1000&lines=Data+Engineer+%7C+Business+Intelligence;Transforming+complex+data+into+meaningful+insights;SQL%7C+Python%7C+Databricks%7C+dbt%7C+CI/CD%7C+Power+BI%7C+AWS;14+years+of+working+with+SQL%7C+Pyspack+skills%7C+Python+for+Data+Analysis" alt="Typing SVG" />
</div>

<!-- 🔗 Update these links with your own social media and contact information -->
<p align="center">
  <a href="https://www.linkedin.com/in/tajudeen-omotosho-12ba39a9/"><img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin"></a>
  <!-- <a href="mailto:youremail/destination"><img src="https://img.shields.io/badge/Email-Contact-green?style=for-the-badge&logo=gmail"> </a> --> 
 <!-- <a href="mailto:taju.omot@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact-green?style=for-the-badge&logo=gmail">
</a> -->

</p>

## 🚀 About Me 
I started my career in audit and accounting, where the job is to prove that numbers are complete, accurate and explainable. I now apply the same discipline to data engineering: control totals between layers, tested exceptions, point-in-time history, and no hindsight in the analysis.

I also develop clear, dynamic dashboards in Power BI and Tableau that communicate insights effectively to stakeholders. My work is driven by precision, clarity, and a commitment to delivering high-quality analytical solutions.

I am looking for data engineering roles (analytics engineering, data platform, or finance and risk data teams) where that background is an advantage.

 <!--🌐 Replace "your-username" with your actual GitHub username -->
<!--### [🏆 Check Out My Full Portfolio Website](https://your-username.github.io/)-->
      
## 🔭 Featured project

- **💳 Credit Card Reconciliation and Fraud Detection (Databricks + dbt):**
- An end-to-end medallion pipeline (bronze, silver, gold) built with dbt on Databricks. It cleans 13.3 million card transactions, tracks card history with a Type 2 slowly changing dimension, runs internal reconciliation checks, and compares a fraud model with a rule baseline using time-based evaluation.
  
```mermaid
flowchart LR
    A[CSV and JSON files<br/>Databricks volume] --> B[Raw Delta tables]
    B --> C[Bronze views]
    C --> D[Silver tables<br/>typed and cleaned]
    D --> E[Gold models]
    E --> F[Fraud rules and model]
    E --> G[Reconciliation checks]
    E --> H[Type 2 card dimension]
```
  

 <!-- - **Content Creation:** [e.g., Developing new tutorials on data visualization for my YouTube channel.]-->

## 🌱 Results at a glance
| Area | Result |
|---|---|
| Scale | 13,305,915 transactions, 6,146 cards, 2,000 users (2010 to 2019) |
| Quality | 63 dbt models and tests pass in a full build, including no overlaps, no gaps and one current row per card in the Type 2 dimension |
| Reconciliation | Counts and amounts tie across bronze, silver, gold and the card-month statement. Exceptions carry severities, and 660,049 refunds were matched to purchases |
| Fraud model (2019, scored once) | Caught 85% of fraud against 60% for the best rule, at the same review workload (same 3.3% of transactions flagged) |
| Method | Time-based split, no leakage, rules and model compared at an equal flag rate |
<!-- - [Another skill, e.g., Cloud data warehousing with Google BigQuery.]-->

## 🛠️ Technical Skillset

<!-- This section uses Shields.io badges. You can customize them or create your own!-->

#### Data Analysis & Visualization
<p>
  <!-- 💡 Go to Shields.io to create your own badges A/B Testing Skill Badg-->
  <img src="https://img.shields.io/badge/SQL-Advanced-4479A1?style=flat&logo=mysql&logoColor=white" alt="SQL Skill Badge">
  <img src="https://img.shields.io/badge/Power%20BI-Expert-F2C811?style=flat&logo=powerbi&logoColor=black" alt="Power BI Skill Badge">
  <img src="https://shields.io"/badge/Databricks%20BI-Expert-F2C811?style=flat&logo=databricks&logoColor=red" alt="Databricks Skill Badge">
  <img src="https://img.shields.io/badge/Tableau-Intermediate-E97627?style=flat&logo=tableau&logoColor=white" alt="Tableau Skill Badge">
</p>

#### Programming & Automation
<p>
  <img src="https://img.shields.io/badge/Python-Intermediate-3776AB?style=flat&logo=python&logoColor=white" alt="Python Skill Badge">
</p>

#### Business Intelligence & Analytics
<p>
  <!--<img src="https://img.shields.io/badge/A%2FB%20Testing-Experienced-FF6B6B?style=flat" alt="A/B Testing Skill Badge">-->
  <img src="https://img.shields.io/badge/Statistical%20Analysis-Experienced-4ECDC4?style=flat" alt="Statistical Analysis Skill Badge">
  <img src="https://img.shields.io/badge/Predictive%20Modeling-Intermediate-45B7D1?style=flat" alt="Predictive Modeling Skill Badge">
  <img src="https://img.shields.io/badge/KPI%20Development-Expert-96CEB4?style=flat" alt="KPI Development Skill Badge">
</p>

## 👋 Professional Experience  
#### Audit & Accounting (2008 - 2015)
- Performed accurate bank reconciliations, ensuring 100% alignment with internal records.
- Produced cashbooks, trial balances, and final accounts, reducing month-end close by 30% using advanced Excel.
- Delivered accurate, client-focused financial reporting.
  
#### Software & Web Developer (2015 – 2021)
- Developed multiple websites and collaborated on web applications using PHP and MySQL.
- Built data-driven application features and improved system performance.
- Worked with distributed teams using digital tools for planning and deployment.
