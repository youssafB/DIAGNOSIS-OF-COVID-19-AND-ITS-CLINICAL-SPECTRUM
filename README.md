PROJECT: DIAGNOSIS OF COVID-19 AND ITS CLINICAL SPECTRUM
In this project, my aim is to apply and enhance my theoretical knowledge by working with a real dataset related to the diagnosis of COVID-19 and its clinical spectrum. The specific strategy involves the following steps:

    ##1 Define a Measurable Objective:
        Objective: Predict whether a person is affected by the coronavirus based on available clinical data with a recall rate of 70%.

    ##2 Exploratory Data Analysis (EDA):
        - Objective: Gain maximum understanding of the dataset to chose a robust modelization strategy.
        - Check out the detailed EDA report for this project [here](link_to_eda_report).
        - View the Jupyter Notebook for EDA [here](link_to_jupyter_notebook).

     ##3 Data Preprocessing:
        - Objective: Transform the data into a suitable format for building the machine learning model.
        - Data Preprocessing Strategy: In my data preprocessing strategy, I adopt an iterative approach that begins with essential preprocessing activities such as encoding categorical variables and handling missing values.

     ##4 Modeling:
        Goal: Build machine learning models that fulfill our defined objective.
        View the Jupyter Notebook for Modeling [here](link_to_jupyter_notebook).




        
### Form Analysis

    Target Variable: SARS-Cov-2 exam result
    Rows and Columns: 5644 rows, 111 columns
    Variable Types: 70 qualitative, 41 quantitative
    Missing Values Analysis:
        Numerous NaN values (over 90% for half of the variables)
        Two data groups with 76% and 89% missing values, related to viral tests and blood levels

### Background Analysis

    Target Visualization:
        10% positive cases (558 out of 5000)

    Variable Significance:
        Standardized continuous variables, skewed distributions, blood test results
        Age quantile: Interpretation is challenging; these data seem processed, and clarity is lacking. While not crucial, it's worth investigating further.
        Qualitative variable: Binary (0, 1), high occurrence of positive viral and Rhinovirus cases

    Variables/Target Relationships:
        Target/blood: Monocytes, Platelets, Leukocytes levels appear linked to COVID-19 - hypothesis to test
        Target/age: Low-age individuals seem less affected - caution, age is unknown, and dataset date is unclear
        Target/viral: Rare double infections, e.g., Rhinovirus/Enterovirus positive - COVID-19 negative, warrant further investigation

### Detailed Analysis

    Variable/Variable Relationships:
        Blood_data/blood_data: Some variables highly correlated (+0.9, to monitor)
        Blood_data/age: Weak correlation between age and blood levels
        Viral/viral: Influenza rapid test shows poor results, consideration for exclusion
        Disease/blood data relationship: Blood levels differ between sick and COVID-19 cases
        Hospitalization/disease: Interesting for predicting patient service allocation

    NaN Analysis:
        Viral: 1350 (92/8), Blood: 600 (87/13), Both: 90

### Null Hypotheses (H0)

    Individuals with COVID-19 have significantly different Leukocytes, Monocytes, Platelets levels.
        H0: Mean levels are EQUAL between positive and negative individuals.

    Individuals with any disease have significantly different levels.
