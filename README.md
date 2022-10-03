# Irish Sea Analysis

### Data Science Case: Performing Time Series Prediction

<img src="image/github_cover.png" width="1000">

## 1. Abstract

## 2. Pipeline

The CRISP-DM methodology was the guide for this data science project development. 

CRISP-DM, which stands for Cross-Industry Standard Process for Data Mining, is an industry-proven way to guide your data mining efforts and it includes descriptions of the typical phases of a project, the tasks involved with each phase, and an explanation of the relationships between these tasks.

<img src="image/crisp_process.jpg" width="500">

**Source:* [IBM Docs](https://www.ibm.com/docs/en/spss-modeler/18.2.0?topic=dm-crisp-help-overview)

To direct your reading, below are links to the development carried out at each stage of the CRISP cycle:

* [Business Understanding](https://github.com/vitorhmf/irish-sea#3-business-understanding)
* [Data Understanding](https://github.com/vitorhmf/irish-sea#4-data-understanding)
* [Data Preparation](https://github.com/vitorhmf/irish-sea#5-data-preparation)
* [Machine Learning Modeling](https://github.com/vitorhmf/irish-sea#6-machine-learning-modeling)
* [Evaluation](https://github.com/vitorhmf/irish-sea#7-evaluation)
* [Depoyment](https://github.com/vitorhmf/irish-sea#8-deployment)

## 3. Business Understanding

### 3.1. Context

### 3.2. Business assumption:

[Back to the top](https://github.com/vitorhmf/irish-sea#2-methodology)


## 4. Data Understanding

### 4.1. Data Cleaning

To build an overview of the data, the following steps were performed:
* Change the columns name to sneak_case;
* Shows the data dimensions (rows and columns);
* Check and Fillout NA: The initial dataset contained 135,080 records without the customer ID. As it represents about 25% of the total, this data could not simply be disregarded. To try to solve this problem, an attempt was made to create client ids from the number 19000 for each record that did not contain this attribute. However, this strategy generated a bias in the data analysis, as it considerably increased the number of customers who made only one purchase. In this way, the data without the customer ID was actually eliminated.

### 4.2 Data Descriptive: 

A quick descriptive analysis of numerical and categorical variables was performed.
 
**Numerical Attributes:**

<img src="image/num_attributes.png" width="700">

Negative quantity and unit price indicate returns. These cases will be dealt with later.

**Categorical Attributes:**

<img src="image/cat_attributes.png" width="650">

The fact that the invoice number and stock code features appear as categorical attributes indicates that we have some records that have letters in their compositions and not just numbers as would normally be expected.

### 4.3. Data Filtering

### 4.4. Feature Engineering

### 4.5. Exploratory Data Analysis

[Back to the top](https://github.com/vitorhmf/irish-sea#2-methodology)


## 5. Data Preparation

### 5.1 Feature Transformation:

### 5.2 Feature Selection: 

[Complete Notebook](https://github.com/vitorhmf/cross-sell/blob/main/notebooks/v07_cross_sell_review2.ipynb) | 
[Back to the top](https://github.com/vitorhmf/irish-sea#2-methodology)


## 6. Machine Learning Modeling

[Back to the top](https://github.com/vitorhmf/irish-sea#2-methodology)

## 7. Evaluation

[Back to the top](https://github.com/vitorhmf/irish-sea#2-methodology)

## 8. Deployment

[Back to the top](https://github.com/vitorhmf/irish-sea#2-methodology)

## 9. Conclusion

### 9.1. Business Results

### 9.2. Next Steps

[Back to the top](https://github.com/vitorhmf/irish-sea#2-methodology)

## 10. References

[Back to the top](https://github.com/vitorhmf/irish-sea#2-methodology)





