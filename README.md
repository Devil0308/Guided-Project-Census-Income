## Problem Statement:
In this project, initially you need to preprocess the data and then develop an
understanding of the different features of the data by performing exploratory
analysis and creating visualizations. Further, after having sufficient knowledge
about the attributes, you will perform a predictive task of classification to predict
whether an individual makes over 50,000 a year or less by using different
machine learning algorithms.

---

## Project Objective:
The goal of this machine learning project is to predict whether a person makes over 50K a year or not given their demographic variation. To achieve this, several classification techniques are explored and the random forest model yields to the best prediction result.

---

## Data Description
1. **Categorical Attributes**

  - ***Workclass***: Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.
Individual work category
  - ***Education***: Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
Individual's highest education degree
  - ***Marital-status***: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
Individual marital status
  - ***Occupation***: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces. Individual's occupation
  - ***Relationship***: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried. Individual's relation in a family
  - ***Race***: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black. Race of Individual
  - ***Sex***: Female, Male.
  - ***Native-country***: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands. Individuals Native Country

2. **Continuous Attributes**

  - ***Age***: continuous, age of an individual
  - ***Fnlwgt***: final weight, continuous, 
The weights on the CPS files are controlled to independent estimates of the civilian noninstitutional population of the US. These are prepared monthly for us by Population Division here at the Census Bureau.
  - ***Capital-gain***: continuous.
  - ***Capital-loss***: continuous.
  - ***Hours-per-week***: continuous, individual's working hour per week

---

## Data Pre-processing Steps
The pre-processing of the data included the following steps:
1. Step 1: Load Data
2. Step 2: Perform ***Exploratory Data Analysis***
    - Confirm number of records in the data and how they are distributed
    - Check data types
    - Check for missing data, invalid entries, duplicates
    - Examine the correlation and multicolinearity betwen independent features with the target (Income) variables.
    - Check for outliers that are known to distort predictions.
3. Step 3: See relations between independent and dependent variables and make inferences.
4. Step 4: Model Predictions for classification,  approaches:
    - Logistic Regression Model.
    - KNeighbors Classifier Model.
    - DecisionTree Classifier Model.
    - GaussianNB Model.
    - RandomForestClassifier Model
5. Step 5: Compare the different algorithm models.
6. Step 6: Choose the best model and predict results.

--- 

## Data Visualization And Insights
### 1. Relationships Of Continuous variables with Target variable:-
  1. **Age**:
        - Hypothesis Test:-
            - *Null Hypothesis* :- there is no difference in Mean age of income group >50k and income group <=50k.
            - *Alternate Hypothesis* :- there is difference in Mean age of income group >50k and income group <=50k.
  ![](Images/image012.png)
  ![](Images/image023.png)
            - *Using Statistical Analysis*:- We can conclude that there is a significant difference in the mean ages of income group >50k and income group <=50k.
It means that age has some contribution to the distinguish income groups.
  2. **Hours per week**
       - Hypothesis Test:-
            - *Null Hypothesis* :- there is no difference in Mean Hours per Week of income group >50k and income group <=50k.
            - *Alternate Hypothesis* :- there is difference in Mean Hours per Week of income group >50k and income group <=50k. 
   ![](Images/image013.png)
   ![](Images/image022.png)
            - *Using Statistical Analysis*:- We can conclude that there is difference in Mean Hours per week of income group >50k and income group <=50k.
It means that hours-per-week has some contribution to the distinguish income groups.
  3. **fnlwgt**:
       - Hypothesis Test:-
            - *Null Hypothesis* :- there is no difference in Mean fnlwgt of income group >50k and income group <=50k.
            - *Alternate Hypothesis* :- there is difference in Mean fnlwgt of income group >50k and income group <=50
   ![](Images/image014.png)
   ![](Images/image021.png)
            - *Using Statistical Analysis*:- We can conclude that there is no difference in Mean fnlwgt of income group >50k and income group <=50k.
It means that final weight has no contribution to the distinguish income group.
   4. **Capital-gain**:
        - Hypothesis Test:-
            - *Null Hypothesis* :- there is no difference in Mean Capital gain of income group >50k and income group <=50k.
            - *Alternate Hypothesis* :- there is difference in Mean Capital gain of income group >50k and income group <=50
   ![](Images/image015.png)
   ![](Images/image020.png) 
            - *Using Statistical Analysis*:- We can conclude that there is difference in Mean Capital-gain of income group >50k and income group <=50k.
   5. **Capital-loss**:
         - Hypothesis Test:-
            - *Null Hypothesis* :- there is no difference in Mean Capital loss of income group >50k and income group <=50k.
            - *Alternate Hypothesis* :- there is difference in Mean Capital loss of income group >50k and income group <=50
   ![](Images/image016.png)
   ![](Images/image024.png)
            - *Using Statistical Analysis*:- We can conclude that there is no difference in Mean capital Loss of income group >50k and income group <=50k.
It means that capital-loss is unable to seperate the income groups.
### 2. Relationships of categorical variables with Target variable:-
  1. **


---
