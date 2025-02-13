
# Diabetes Prediction
## by DEBORAH KOLA ADEMOLA
___
## INTRODUCTION
___
Diabetes affects millions of people worldwide, and understanding what puts certain groups at higher risk is crucial for prediction, prevention and management which are the main aims of this analysis. 
In this analysis, I looked at a diabetes prediction dataset from KAAGLE covering over 96,000 individuals to explore how factors like age, BMI, and smoking habits are linked to diabetes.  
___

## PROBLEM STATEMENT
___

The purpose of this analysis is to get insight of which risk factor is more associsated with diabetes, exploring how each of these factors are linked to diabetes. I am interested in;
* finding out how smoking is inked to diabetes
* the relationship between body mass index and diabetes
* if truly age is, in some way, linked to diabetes
___
## DATA SOURCING
___
This is a dataset gotten from [KAGGLE](https://www.kaggle.com/)

Here's the link to the dataset [DATASET](https://www.kaggle.com/code/tumpanjawat/diabetes-eda-random-forest-hp/input)
___
## SKILLLS DEMONSTRATED
___
For this project, I optimized EXCEL for data cleaning,transformation and visualization.
___
## DATA CLEANING.
___
The dataset was very dirty with missing values,duplicates and blanks. I did lots of cleaning using Excel but I'll walk through the most import parts  
![image alt](https://github.com/Temitope-Kola/Diabetes-Analysis/blob/main/IMAGES/DIRT_%20DATA.png?raw=true)
___

## DATA TRANSFORMATION

* The dataset had fewwer columns as compared to after I transformed it. I observed, to get the most out of the dataset, it was important to create more columns from the existing columns.
* I transformed the data using very complex Excel functions, combining the IF function alomgside OR.
* I was able to do this by carefully going through each column and understanding what must be done, it was very delightful to see that, the transformation I had made provided better perspective to my analysis.
![image alt](https://github.com/Temitope-Kola/Diabetes-Analysis/blob/main/IMAGES/CLEANED_DATA.png?raw=true)
![image alt](https://github.com/Temitope-Kola/Diabetes-Analysis/blob/main/IMAGES/FORMULAR_SS.png?raw=true)
___

## ANALYSIS AND VISUALIZATION
___  
![image alt](https://raw.githubusercontent.com/Temitope-Kola/Diabetes-Analysis/efbccfe2a3538e490f05885bab4f709aa94fd961/IMAGES/UPDATE%20DASHBOARD.png)  

This dashboard has a single report page.
___
I am interested in;
* finding out how smoking is linked to diabetes
* the relationship between body mass index and diabetes
* if truly age is, in some way,is linked to diabetes.

___

* # finding out how smoking is linked to diabetes.
___  
![image alt](https://github.com/user-attachments/assets/9f221229-6c7d-435d-9d86-8b665ae591c6)

* No Info: The majority of individuals (31,442) have no smoking history provided, with 1,445 diabetes cases. 4.39% have diabetes.
* Current smokers: 948 diabetes cases, suggesting a potential risk factor. 10.31% have diabetes, suggesting a strong association.
* Former smokers: 1,590 diabetes cases, Diabetes prevalence rises to 17.10%, indicating lingering health effects of smoking.
* Never and ever smokers: 3,807 diabetes cases, the highest in this category, 9.95% have diabetes.
* Not current smokers: 690 diabetes cases,10.84% have diabetes.

___
* # the relationship between body mass index and diabetes.
  ___
 ![image alt](https://github.com/Temitope-Kola/Diabetes-Analysis/blob/main/IMAGES/BMI_SS.png?raw=true)
 
 * Obese individuals: 4,277 cases of diabetes, 17.91% have diabetes, the highest among BMI categories.
* Overweight individuals: 3,300 cases, 7.90% have diabetes, despite being the largest group overall.
* Normal BMI individuals: Fewer diabetes cases (839), suggesting lower risk. Only 3.84% have diabetes, highlighting the protective effect of a healthy weight.
* Underweight individuals: Only 64 cases of diabetes, the lowest among all groups. Hence Diabetes prevalence is very low at 0.75%.
  ___
  
* # if truly age is, in some way,is linked to diabetes.
___  
![image alt](https://github.com/Temitope-Kola/Diabetes-Analysis/blob/main/IMAGES/AGE_SS.png)

* Ages 0-20: 18,925 individuals without diabetes, but only 106 with diabetes. Only 0.56% have diabetes, showing very low prevalence.
* Ages 21-40: Diabetes cases increase slightly (603 individuals) among 24,001 without diabetes. Diabetes prevalence increases to 2.45%.
* Ages 41-60: A notable rise in diabetes cases (2,854) compared to earlier age groups. A significant rise to 10.04%, suggesting increased risk after 40.
* Ages 61-80: A significant increase in diabetes prevalence (3,904 cases). Diabetes prevalence jumps to 20.53%, indicating a high-risk group.





# CONCLUSION
___
*	Age and Diabetes:
	Diabetes prevalence increases significantly with age, particularly after 40 years, Peaking at over 20% for individuals 61 years and older.
*	BMI and Diabetes:
Obesity is strongly associated with diabetes, with nearly 18% of obese individuals affected. Maintaining a healthy BMI significantly reduces diabetes risk.
 *	Smoking and Diabetes:
Current and former smokers have significantly higher diabetes prevalence (10-17%), compared to non-smokers and those with no history (~4%).

