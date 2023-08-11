# Diabetes Prediction and Risk Factor Analysis

### Team Members
Taylor Erickson 

### Description of the Project
This project leverages logistic regression and multinomial logistic regression modeling techniques to identify whether there is a meaningful difference between the predictors (or risk factors) of prediabetes vs. diabetes. This is to address the relative lack of investigation into prediabetes and diabetes as distinct states of hyperglycemia, and the significant number of individuals with prediabetes who go undiagnosed until they eventually develop life-threatening diseases or symptoms, including Type II diabetes. As the incidence of prediabetes, diabetes, and related hyperglycemia conditions increase, it is imperative to understand how best to identify and treat at-risk populations. 

### Summary of the questions sought and the answers

__What are the strongest predictors of prediabetes and diabetes?__
The strongest predictors of prediabetes and diabetes are health related factors:
BMI
Stroke
Physical Health
Heart Attack
High Blood Pressure


While there were similarities between what were strong predictors of diabetes and prediabetes, there were some interesting differences, particularly when fitting a logistic regression model to predict classificaiton of diabetes. While recursive feature elimination identified the same top 5 features as the strongest predictors, the initial logistic regression model for diabetes included significant coefficient values and good model performance for a model fit additional features, including Smoker, No Doctor because of Cost, Mental Health, Sex, Marital Status, and Poor Health.

__Are there meaningful differences between the predictors of prediabetes and diabetes, or are they similar?__
There are not meaningful differences in the identified predictors of prediabetes and diabetes. The same features were identified for both prediabetes and diabetes were identfied when creating best fit models. However, the strength of the association is not uniform, and there are many more strong predictors of diabetes than prediabetes. 


__Do these sets of predictors match existing screening standards?__
These sets of predictors do mirror existing screening standards, either directly or indirectly. For example, existing screening standards identify obesity and overweight individuals as being at higher risk of prediabetes and diabetes, while we fit our model based on BMI category. Additionally, we identified stroke, poor physical health and heart attack as strong predictors, but medical literature that surveys longitudinal studies has identified those attributes as outcomes of diabetes, rather than predictors of developing diabetes after experiencing that event. A limitation of our model is that it is not conducted using longitudinal data, so we can only consider the comorbidity of certain conditions rather than their relative pathogenesis. 

### Application of this Knowledge
This knowledge can be applied to inform the general public about their relative risk for diabetes and prediabetes, especially since prediabetes often goes undiagnosed. Additionally, the findings of the diabetes logistic regression model can be used to identify future research areas for additional attributes of investigation to understand why significant predictors of diabetes were not associated with prediabetes, if the assumption is made that prediabetes is a preceding state to diabetes. Finally, these findings replicate existing research into diabetes and prediabetes risk factors, providing further evidence of the comorbidity of prediabetes and diabetes with many deleterious health outcomes compared to the general population. 



### Final Project Paper

https://github.com/taer7274/CSPB4502_group2_diabetes/blob/main/02_DiabetesPrediction%26RiskFactorAnalysis_Part4.pdf
