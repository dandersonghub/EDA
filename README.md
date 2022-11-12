# [Exploratory Data Analysis (EDA) & Linear Regression](https://github.com/dandersonghub/Exploratory-Data-Analysis/blob/main/EDA_Linear_Regression.ipynb)
This project demonstrates the process of using EDA to clean a dataset, understand the variables, and analyze the relationships between variables using Simple Linear Regression and Multiple Linear Regression modeling. A survey dataset of population health-related data was explored in this project and a simple linear and multiple linear regression were modeled in order to determine the main features that predict systolic blood pressure 'BP'.

Descriptive statistics and Pearson correlation coefficients were calculated to review and compared the relationships between the target and 7 potential predictor variables. The variable 'AGE' was determined to be a statistically significant predictor of blood pressure with a moderate correlation of 0.46 and a p-value <0.001. Ninteen percent of the variation in systolic BP is explained by age. Variables for age, smoking status, and, BMI were modeled to explain the variation in blood pressure. 
After controlling for BMI, the age and smoking status effects on blood pressure decreased. After modeling, 20% of the variation in BP can be explained by age, smoking status, and, BMI. 

### Correlation Heatmap
![](https://github.com/dandersonghub/Exploratory-Data-Analysis/blob/main/Heatmap.png)
### Simple Linear Regression
![](https://github.com/dandersonghub/Exploratory-Data-Analysis/blob/main/SLR_.png)
