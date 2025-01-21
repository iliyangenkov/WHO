# WHO Life Expectancy Prediction

## Team Members:

@AF332 -- Arif Faisal

@iliyangenkov -- Iliyan Genkov

@JBrennan2001 -- Joseph Brennan

## Project Overview

This project aims to analyze and predict life expectancy for the World Health Organisation using a linear regression model. By identifying patterns and predictors of life expectancy, countries are able to take proactive measures to improve health and wellbeing on a individual, group and country level. 

The key deliverables include:
1. An advanced linear regression model aimed at maximising predictive power. 
2. A minimalist, ethical linear regression model aimed at addressing ethical concerns around data privacy. Some countries have expressed concerns over providing medical records of their citizens, and this model hopes to maintain data privacy at the cost of a slightly lower predictive power.
3. An interactive function that can be released to countries, allowing them to choose between the full or minimalist model, input their values, and give a prediction of their life expectancy.

## Key Features

1. **Data Cleaning**  
   The raw dataset undergoes a rigorous cleaning process to check for:  
   - Missing values
   - Value alignment with metadata
   - Irrelevant features
   - Inconsistent data formats
   - Inconsistent scaling

2. **Exploratory Data Analysis (EDA)**
   Gain insights from the dataset through:
   - Visualising key patterns and trends
   - Uncover the key factors that affect life expectancy
 		
3. **Feature Selection and Engineering (FE)**  
   Considered the ethical concerns of using certain features, and made careful judgements on what to exclude from our ethical model.

   We then transformed raw data into meaningful features to improve model performance. This includes:  
   - Encoding categorical variables  
   - Scaling continous variables
   
   The FE process had to be adapted to work for the advanced and minimalist model, given the different features selected.

4. **Model Building & Evaluation**  
   Using linear regression to predict life expectancy and evaluating model performance with metrics such as Root Mean Square Error (RMSE) and Mean Absolute Percentage Error (MAPE).
 
   This was an iterative process that involved exploring a wide variety of model specifications, and selecting the best performing advanced and ethical model.

5. **Function Building**
   Using the models we have selected, we create an interactive function that asks the user which model they want to use and then receives inputs to predict life expectancy.

---

The bulk of the project is split into multiple notebooks based on the stages in the data project lifecycle:
 1. EDA.ipynb: step-by-step implementation of data cleaning and EDA.
 2. advanced_model.ipynb: feature selection, feature engineering, model building and evaluation of full-fledged model.
 3. ethical_model.ipynb: feature selection, feature engineering, model building and evaluation of minimalist model aimed at maintaining data privacy.
 4. life_expectancy_function.ipynb: an interactive function that can be released to countries for predicting life expectancy through inputting their own data.

These are the main notebooks. Additional files include the dataset and metadata provided by the WHO (Life Expectancy Data.csv and WHO Dataset - MetaData.ipynb), as well as any saved parameters/models that can be used to run the function as a self-contained notebook (these files need to be saved in the same directory as the notebook).  
 
