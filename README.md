# nairobihospital
Hypothyroidism prediction.
Using Decision Trees and Support Vector Machines to Build a model that determines whether or not a patient's symptoms indicate that the patient has hypothyroidism or not.

  a) Defining the Question
As a Data Scientist, I have been recruited to work for Nairobi Hospital which is a private hospital in Kenya. I have been tasked to create a model that determines whether or not the patient's symptoms indicate that the patient has hypothyroidism or not.

  b) Defining the Metric for Success
This project will be successful when:

1)We Identify the most crucial independent variables that affect Hypothyroidism.

2)The model achieves atleast 80% accuracy

3)Have the lowest RMSE score possible

  c) Understanding the context: Factors that increase the risk for hypothyroidism

Are older than 60

Have a family history of thyroid disease

Have an autoimmune disease, such as type 1 diabetes or celiac disease

Have been treated with radioactive iodine or anti-thyroid medications

Received radiation to your neck or upper chest

Have had thyroid surgery (partial thyroidectomy)

Have been pregnant or delivered a baby within the past six months

  e)Experimental Design
The project was undertaken using the following design Datasets(hypothyroid.csv)

Exploratory Data Analysis

Data Cleaning

Univariate Analysis

Bivariate Analysis

Multivariate Analysis

Modelling

Decision Trees: Random Forests , Ada Boosted Trees 

Support Vector Machines: Kernel = polynomial , linear , rbf

Conclusion


The tuned Ada Boosted Trees model was the best model for the Decision Trees and the linear kernel was the best for the Support Vector Machines.


The XGBoost model can also be a good solution for this since it deals with computational power which proved a challenge in my analysis.
