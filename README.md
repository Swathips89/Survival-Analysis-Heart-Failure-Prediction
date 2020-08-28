# Survival-Analysis-Heart-Failure-Prediction
Survival Analysis using Kaplan Meier estimator and Cox proportional model

Cardiovascular diseases (CVDs) are the number 1 cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worlwide.

Heart failure is a common event caused by CVDs and this dataset contains 12 features that can be used to predict mortality by heart failure.

Age, serum sodium, serum creatinine, gender, smoking, Blood Pressure (BP), Ejection Fraction (EF), anemia, platelets, Creatinine Phosphokinase (CPK) and diabetes were considered as potential variables explaining mortality caused by CHD. Age, serum sodium and CPK are continuous variables whereas EF, serum creatinine and platelets were taken as categorical variables. EF was divided into three levels (i.e. EF≤30, 30<EF≤45 and EF>45) and platelets was also divided into three level on the basis of quartiles. Serum creatinine greater than its normal level (1.5) is an indicator of renal dysfunction. Its effect on mortality was studied as creatinine >1.5 vs ≤1.5

# Output
# Logistic regression - Accuracy : 78.89%
# Cox model output –
1) Coefficient concerning age indicated that chances of death due to CHD increase with growing age. Hazard of death due to CHD increases by 5% for every additional year of age. 
2) Anemia was significant with p-value = 0.02. It means death hazard increases by 67% for a person who is anemic than a non-anemic person 
3) Creatinine phosphokinase was significant with p-value=0.01.It means as the levels increase the death hazard increases.
4) High blood pressure was significant with p-value = 0.02. It means death hazard increases by 66% for a person who has high blood pressure than a person with a low blood pressure
5) Serum creatinine was significant with p-value = 0.03. It means death hazard increases by 22% for unit increase in Serum creatinine. 

# Conclusion
It can be concluded that growing age, having serum creatinine greater than its normal level 1.5, high BP (higher than normal range), higher level of anemia are the key factors contributing towards increased risk of mortality among heart failure patients. No significant differences were found due to smoking status, diabetes, serum sodium levels and gender of patients.
