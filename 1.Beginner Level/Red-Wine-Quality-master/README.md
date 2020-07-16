# Red Wine Quality Predicition

## 1.Business Problem

### 1.1 Description
The datasets are related to red wine of the Portuguese "Vinho Verde" wine. For more details, consult the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones).



### 1.2 Sources
https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009

## 2.Machine Learning Problem

### 2.1 Data
#### 2.1.1 Data Overviews
Contain one files 
* <b>weight-height.csv</b>-containing 1599 data points an 12 features</br>

#### Attribute-information
* fixed acidity 
* volatile acidity 
* citric acid 
* residual sugar 
* chlorides 
* free sulfur dioxide 
* total sulfur dioxide 
* density 
* pH 
* sulphates 
* alcohol 
* Output variable (based on sensory data): 
* quality (score between 0 and 10) 

### 2.2 Mapping the real-world problem to a Machine Learning Problem
#### 2.2.1 Type of Machine Learning Problem
Classification Problem predit Wine is good quality or bad Quality

#### 2.2.2 Performance metric
F1-score
