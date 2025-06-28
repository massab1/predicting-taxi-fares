# predicting-taxi-fares
Portfolio project using ML for classification/prediction tasks
# Predicting Taxi Gratuities in New York City

## 🧠 Project Overview
Built regression and random forest models to predict generous tippers using NYC taxi data. Random forest achieved 86% accuracy and 72% precision. Most important factors: duration, cost, and distance.

## 🎯 Business Understanding
Taxi drivers in NYC struggle to earn livable wages. Predicting high-tipping trips can help optimize service strategies and income potential.

## 📊 Data Understanding
Data from NYC TLC (2017), ~408,000 trips. Features: fare amount, duration, distance, payment type. Missing and redundant data cleaned.

## 🤖 Modeling & Evaluation
Used scikit-learn’s RandomForestClassifier. Key evaluation metrics: Accuracy (86%), Precision (72%). Visualized top features using feature importance chart.

## ✅ Conclusion
Drivers can identify better routes and service strategies. Future models may include customer tipping history and real-time ride context.
Predicting Taxi Gratuities in New York City

Overview 
The goal of this project was to create a multiple linear regression and random forest model to predict high rider gratuity or not. This project utilized yellow taxi trips taken in New York City during 2017. The final random forest model performed with 86% accuracy and 72% precision determining what features were most important in separating low tippers from high tippers. Based on the model, the duration, distance, and cost of the trip were most influential in determining a generous tipper (>20%) vs a non-generous one (<20%). 

Business Understanding 
According to salary.com the average salary for a New York Taxi Driver is around $45,000. This salary is significantly low compared to a median rent value of $6,500 per month. It is important to understand what factors encourage riders to leave tips in order to help drivers obtain a livable wage. 

Data Understanding
The NYC Taxi and Limousine Commission data came from 
NYC.gov
. The data consisted of approximately 408k unique trips and 18 features. The features included information on trip duration and destination, vendor used, toll information, and payment type. The bar chart below shows the breakdown of how many generous tippers (>20%) versus non-generous tippers that exist in the data set. ![image](https://github.com/user-attachments/assets/2bdb97ae-efa2-4828-b303-c88d90868ba9)
Conclusion
This model can benefit Taxi Drivers in knowing if they will be tipped generously or not; however, running a parametric model to determine how much each variable will influence the actual price of the tip. In the future, adding more information on a rider’s past tipping behavior may also be beneficial in helping the stakeholder address their business problem. 


Outside of the README file, it is important to have the data i used, cleaned up Python notebook files, a presentation, and any images i may have used on your GitHub repository. 
![image](https://github.com/user-attachments/assets/51ce3fc4-0ed3-4671-a0a7-44d4f4f30c3d)

Checked out  additional resource from 
DataQuest
 that walks me through how to add files to your online Github portfolio. The goal is to have all project information in one repository that will help an employer understand your project, run your code, and clearly know your business recommendations.

