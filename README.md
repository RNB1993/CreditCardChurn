# Credit Card Churn Analysis

This project explores customer churn within a credit card portfolio using
Python-based data analytics and visualisation.
The objective is to identify behavioural patterns associated with churn
and demonstrate how data analytics can support evidence-based
retention decision-making.

![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

---

## Dataset Content
The dataset used in this project originates from Kaggle and initially
consists of 21 columns containing anonymised customer-level information.
It includes both existing and churned customers and captures:

- Customer engagement and inactivity metrics
- Product relationship counts
- Transaction frequency and value
- Customer tenure and selected demographic attributes
- Churn indicator (attrited vs existing)

All data preparation and transformation steps are documented
in the ETL notebook.

---

## Business Requirements
The bank has observed an increase in credit card customer attrition,
leading to higher acquisition costs and reduced customer lifetime value.
While demographic data is available, there is limited understanding of
which behavioural and engagement factors most strongly influence churn.

The analytics objective is to identify high-risk churn segments and
provide actionable insights to support proactive retention strategies.

### Business Objectives
1. Identify customer segments with above-average churn rates  
2. Understand behavioural and engagement factors linked to churn  
3. Provide data-backed recommendations to reduce churn  
4. Demonstrate how analytics and AI-assisted insights support decision-making  

---

## Hypotheses and Validation Approach

### Hypothesis 1 — Customer Engagement
Customers with lower engagement, measured by fewer product relationships
and higher inactivity, are more likely to churn.

**Validation approach:**
- Compare churn rates by relationship count
- Compare inactivity distributions between churned and existing customers  
- Visualisations: bar charts and boxplots

---

### Hypothesis 2 — Customer Tenure
Customer tenure influences churn risk, though tenure alone may not be a
sufficient predictor of retention.

**Validation approach:**
- Compare tenure distributions by churn status
- Analyse churn rates across tenure bands  
- Visualisations: histograms and bar charts

---

### Hypothesis 3 — Transaction Behaviour
Customers with lower transaction frequency and lower transaction value
are more likely to churn than active transactors.

**Validation approach:**
- Compare transaction count and transaction value distributions
- Segment transaction behaviour by card category  
- Visualisations: boxplots and supporting segmentation plots

---

## Project Structure
```text
project-root/
│
├── data/
│   ├── rawData/                # Original dataset
│   └── cleanData/          # Cleaned dataset from ETL pipeline
│
├── jupyter_notebooks/
│   ├── ETL.ipynb
│   └── DataVisualisations.ipynb
│
├── README.md
└── requirements.txt

## Project Plan and Methodology

The project follows a structured analytical workflow:

1. Data extraction and validation  
2. Data cleaning and transformation (ETL)  
3. Exploratory and descriptive analysis  
4. Hypothesis-driven visual analysis  
5. Interpretation and business insight generation  

Descriptive analytics was chosen to ensure interpretability and
clear communication of insights to both technical and non-technical audiences.

---

## Mapping Business Requirements to Visualisations

Each visualisation was explicitly designed to address a specific
business question related to churn risk.

Behavioural metrics (transactions, inactivity, engagement)
were prioritised over demographic attributes due to their stronger
association with churn observed in the data.

---

## Analysis Techniques Used

- Data cleaning and aggregation using **Pandas**
- Distribution analysis using summary statistics and boxplots
- Segmentation using categorical grouping and banding
- Comparative visual analysis using **Matplotlib** and **Seaborn**

### Limitations
- The analysis is descriptive and does not establish causality
- Certain lifecycle stages (e.g. very early tenure) are not present in the dataset
- External factors influencing churn are not captured

---

## Use of AI Tools
AI-assisted tools were used to support hypothesis development,
code refinement (MS opilot), and narrative clarity (Grammarly premium).
All AI-assisted suggestions were reviewed and validated
against the dataset prior to inclusion.

---

## Unfixed Issues

No critical bugs were identified that impact the validity of the analysis.
Some visualisations may contain outliers due to the natural distribution
of transaction behaviour, which were intentionally retained
to preserve analytical transparency.

---

## Development Roadmap

### Challenges Encountered
- Interpreting non-linear churn patterns
- Managing class imbalance during exploratory analysis
- Ensuring clarity between supporting and primary visualisations

### Future Development
- Extend the analysis to predictive modelling
- Incorporate time-series behavioural trends
- Integrate additional customer experience variables

---

## Main Data Analysis Libraries

- **Pandas** — data manipulation and aggregation  
- **NumPy** — numerical operations  
- **Matplotlib** — foundational visualisations  
- **Seaborn** — distribution and segmentation analysis  

---

## Credits

- Dataset sourced from Kaggle (BankChurners dataset)  
- Course materials and guidance provided by Code Institute  
- Documentation references from official Pandas and Seaborn documentation  

---

## Acknowledgements

Thanks to Code Institute facilitators and peers for feedback and guidance
throughout the project. You know who you are :) 