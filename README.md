# PROJECT: DIAGNOSIS OF COVID-19 AND ITS CLINICAL SPECTRUM
In this project, my aim is to apply and enhance my theoretical knowledge by working with a real dataset related to the diagnosis of COVID-19 and its clinical spectrum. The specific strategy involves the following steps:

 ## 1 Define a Measurable Objective:
  Objective: Predict whether a person is affected by the coronavirus based on available clinical data with a recall rate of 70%.
        
 ## 2 Exploratory Data Analysis (EDA):
  - ***Objective***: Gain maximum understanding of the dataset to chose a robust modelization strategy.
  - ***Jupyter Notebook*** for EDA [here](https://github.com/youssafB/EDA-project-Cov19/blob/main/EDA-COV19%20.ipynb).
  - ***Exploratory Data Analysis Report:*** For a detailed understanding of the dataset and valuable insights for data preprocessing and model building, an Exploratory Data Analysis (EDA) report has been generated. You can check the report [here](https://github.com/youssafB/EDA-project-Cov19/blob/main/EDA%20Report).

 ## 3 Data Preprocessing:
  - Objective: Transform the data into a suitable format for building the machine learning model.
  - **Data Preprocessing Strategy**:
In my data preprocessing strategy, I adopt an iterative approach that begins with essential preprocessing activities such as encoding categorical variables and handling missing values.Following these basic preprocessing steps, I proceed to build my initial model.Based on the model evaluation and analysis, I selectively incorporate additional preprocessing steps to enhance the model. This stepwise refinement is driven by a conscious choice of preprocessing techniques tailored to the specific challenges and patterns identified during the evaluation phase.
- View the Jupyter Notebook for Preprocessing and intial model building  [here](https://github.com/youssafB/EDA-project-Cov19/blob/main/Preprocessing.ipynb).
<!-- Adjust the width to your preference, e.g., width="500" -->
<img src="https://github.com/youssafB/EDA-project-Cov19/blob/main/strategy.png" alt="Strategy image" width="600">

 ##  4 Modeling
  - ****Goal***: Build machine learning models that fulfill our defined objective.
  - ****Strategy**** : In this step, we will train multiple models, and our selection process involves choosing the model with the best performance. Subsequently, we aim to optimize this selected model using GridSearchCV. Finally, we'll explore how to strike a balance between recall and precision by analyzing precision-recall curves to further enhance our model's performance.
  - View the ****Jupyter Notebook*** for Modeling [here](https://github.com/youssafB/PROJECT-DIAGNOSIS-OF-COVID-19-AND-ITS-CLINICAL-SPECTRUM/blob/main/Modelisation.ipynb).
