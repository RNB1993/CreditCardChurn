# Credit Card Churn Analysis

**Credit Card Churn Analysis** is a comprehensive data analysis tool designed to streamline data exploration, analysis, and visualisation. The tool supports multiple data formats and provides an intuitive interface for both novice and expert data scientists.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* the dataset this project will be using starts off as a 21 column dataset before any ETL actions occur. This holds details about exisitng and churned customers who use products at the bank in question. It is sourced from Kaggle.com 


## Business Requirements
* The bank has observed an increase in credit card customer attrition, impacting revenue and increasing acquisition costs. While customer demographic data is available, leadership lacks clarity on which behavioural and engagement factors most strongly influence churn.

* The analytics team (ME!) has been asked to analyse existing customer data to identify high-risk churn segments and provide actionable recommendations to support proactive retention strategies.

Business Objectives
1.	Identify customer segments with above-average churn rates
2.	Understand behavioural and demographic factors linked to churn
3.	Provide data-backed recommendations to reduce churn
4.	Demonstrate how analytics and AI-assisted insights can support decision-making


## Hypothesis and how to validate?
* List here your project hypothesis(es) and how you envision validating it (them) 
1: Customer Engagement
Customers with lower overall engagement, measured by fewer products held and higher inactivity, are more likely to churn.
Dataset fields
•	Total_Relationship_Count
•	Months_Inactive_12_mon
•	Attrition_Flag
How it will be tested:
•	Group by engagement level
•	Compare churn rates
Plots (ideas)
•	Bar chart: churn rate by relationship count
•	Box plot: months inactive vs churn
Business relevance
Low engagement customers are prime candidates for targeted offers or usage incentives.

2: Customer Tenure
Customers with a shorter tenure (Months_on_book) are more likely to churn than long-standing customers.
Plots
•	Histogram: tenure distribution by churn status
•	Bar chart: churn rate by tenure band
Business relevance
Supports lifecycle-based onboarding and early intervention strategies.

3: Transaction Behaviour
Customers with lower transaction frequency and value are more likely to churn than active transactors.
Plots
•	Box plot: transaction count by churn status
•	Scatter plot: transaction count vs amount (coloured by churn)
Business relevance
Identifies customers at risk due to declining card usage.

 4: Demographics vs Behaviour (need to make to an business idea) may drop if time short 
While certain demographic segments show higher churn rates, behavioural variables are stronger indicators of churn than demographics alone.
Dataset fields
•	Demographics: Customer_Age, Gender, Income_Category
•	Behavioural: transactions, inactivity, tenure


## Project Plan
* Outline the high-level steps taken for the analysis.
* How was the data managed throughout the collection, processing, analysis and interpretation steps?
* Why did you choose the research methodologies you used?

## The rationale to map the business requirements to the Data Visualisations
* List your business requirements and a rationale to map them to the Data Visualisations

## Analysis techniques used
* List the data analysis methods used and explain limitations or alternative approaches.
* How did you structure the data analysis techniques. Justify your response.
* Did the data limit you, and did you use an alternative approach to meet these challenges?
* How did you use generative AI tools to help with ideation, design thinking and code optimisation?

## Ethical considerations
* Were there any data privacy, bias or fairness issues with the data?
* How did you overcome any legal or societal issues?

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 
The challenges encounted variey, please see below for details and how i overcame them. 

 ## Development Roadmap




## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)
* Thank the people who provided support through this project.