Allianz is a global financial services company headquartered in Munich, Germany.
Founded in 1890, it is one of the largest insurance and asset management firms in the world.
Allianz serves over 88 million customers across more than 70 countries.

Its services span life and health insurance, property and casualty insurance, and asset management.
The company is also known for its innovation, digital transformation, and commitment to sustainability.

Clustering Algorithms (Unsupervised Learning): 
Group customers and brokers based on characteristics like Broker_cor, Customer_region, and Line_of_business. 
Use these clusters for personalized marketing and policy adjustments. 
Survival Analysis: 
Model time-to-event data (e.g., time to adopt direct debit or time to churn) to optimize retention strategies. 
Propensity Score Modeling: 
Predict the likelihood of a customer switching to direct debit and target interventions accordingly. 
Hierarchical Bayesian Models: 
Incorporate multiple levels of data (customer, broker, product) to account for the nested structure in the dataset. 

Key highlights: 

Challenges Identified: Low conversion rates on T&B's online sales channel compared to other affinities, despite a user-friendly system. 
Data Collection: The team gathered three datasets—funnel, policy, and regional—to analyze customer profiles and behavior. 
Analytical Approach: The CRISP-DM framework was utilized to guide the data analysis process through six phases, emphasizing understanding business objectives, data preparation, modeling, and evaluation. 
Machine Learning Techniques: Both unsupervised (clustering) and supervised (classification) analytics were employed to segment customers and predict conversion likelihood. 
Outcome: Insights derived from the analysis aimed to help tailor marketing campaigns and improve customer acquisition strategies. 

The solution involves analyzing the datasets provided: 
1. Funnel Data Set 
Variables to analyze: 
affinity_name: To compare performance across affinities and identify patterns. 
status_report: To track drop-off points in the process. 
premium: To evaluate how pricing impacts customer decisions. 
birth_date, buildyear_car: To uncover demographic and product preferences. 
Objective: Identify where customers drop off in the funnel and determine any correlation with pricing, demographics, or car attributes. 
2. Policy Data Set 
Variables to analyze: 
policy_start_date and policy_continuation_date: To understand customer retention. 
premium_wa, premium_other: To assess the impact of pricing on renewals. 
gender, place_residence, bonus_malus_percent: To segment customer profiles. 
Objective: Highlight characteristics of existing policyholders and identify factors contributing to continued engagement versus churn.

Regression Models 

Logistic Regression: 
Predict the probability of customers adopting direct debit (Is_direct_debit as the dependent variable). 
Identify key influencing factors like Customer_age, Customer_urbanization, and Annual_premium. 
Linear Regression: 
Explore relationships between variables, such as how Annual_premium correlates with profitability metrics like Broker_cor. 
Predict factors like average claims cost based on demographics or payment methods. 
Multinomial Logistic Regression: 
Analyze outcomes with multiple categories (e.g., Line_of_business) and their influence on profitability or claims ratios. 
Regularization Techniques (Lasso, Ridge): 
Address multicollinearity and feature selection when dealing with high-dimensional data. 
 

Customer Lifetime Value (CLV) Models 

Cohort-Based CLV: 
Segment customers into cohorts based on Customer_segment or Product_type. 
Analyze retention rates, premiums, and claims patterns to calculate profitability over time. 
Probabilistic CLV Models: 
BG/NBD (Beta Geometric/Negative Binomial Distribution):  
Estimate purchase frequency and churn probability for customers. 
Gamma-Gamma Model:  
Predict the monetary value of customers who are actively purchasing. 
Machine Learning-Based CLV Models: 
Train supervised models to predict CLV using features like Customer_region, Payment_frequency, Is_direct_debit, etc. 
Use feature importance to gain insights into key drivers of CLV. 
 

Statistical and Data-Driven Models 

Clustering Algorithms (Unsupervised Learning): 
Group customers and brokers based on characteristics like Broker_cor, Customer_region, and Line_of_business. 
Use these clusters for personalized marketing and policy adjustments. 
Survival Analysis: 
Model time-to-event data (e.g., time to adopt direct debit or time to churn) to optimize retention strategies. 
Propensity Score Modeling: 
Predict the likelihood of a customer switching to direct debit and target interventions accordingly. 
Hierarchical Bayesian Models: 
Incorporate multiple levels of data (customer, broker, product) to account for the nested structure in the dataset. 

Using a time-based definition of churn (continuation date more than one year before the latest policy date), the calculated churn rate is 4.04% across 99 customers. This approach ensures a business-aligned view of customer retention and inactivity.
