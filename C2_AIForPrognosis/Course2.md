 ## Course 2. [AI for Medical Prognosis](https://www.coursera.org/learn/ai-for-medical-prognosis/home/info)

### Week 1. Linear Prognostic Models
Build a linear prognostic model using logistic regression, then evaluate the model by calculating the concordance index. Finally, improve the model by adding feature interactions.
  
Video: Medical Prognosis  
Ungraded Lab: Create a Linear Model  
Video: Examples of Prognostic Tasks  
Video: Atrial Fibrillation  
Video: Liver Disease Mortality  
Video: Risk of Heart Disease  
Ungraded Lab: Risk Scores, Pandas and Numpy  
Video: Risk Score Computation  
Ungraded Lab: Combine Features  
Video: Evaluating Prognostic Models  
Video: Concordant Pairs, Risk Ties, Permissible Pairs  
Video: C-Index  
Ungraded Lab: Concordance Index  
Practice Quiz: Prognostic Models  
 
- Programming Assignment: Build and Evaluate a Linear Risk model


### Week 2. Prognosis with Tree-based Models
Tune decision tree and random forest models to predict the risk of a disease. Evaluate the model performance using the c-index. Identify missing data and how it may alter the data distribution, then use imputation to fill in missing data, in order to improve model performance.


Video: Decision Trees for Prognosis  
Video: Decision Trees  
Video: Dividing the Input Space  
Video: Building a Decision Tree  
Video: How to Fix Overfitting  
Ungraded Lab: Decision Tree Classifier  
Video: Survival Data  
Video: Different Distributions  
Video: Missing Data Example  
Video: Missing Completely at Random  
Video: Missing at Random  
Video: Missing Not at Random  
Ungraded Lab: Missing Data and Applying a Mask  
Video: Imputation  
Video: Mean Imputation  
Video: Regression Imputation  
Video: Calculate Imputed Values  
Ungraded Lab: Imputation  
Practice Quiz: Decision Trees, Missing Data and Imputation  

- Programming Assignment: Risk Models Using Tree-based Models

### Week 3. Survival Models and Time
work with data where the time that a disease occurs is a variable. Instead of predicting just the 10-year risk of a disease, you will build more flexible models that can predict the 5 year, 7 year, or 10 year risk.

Video: Survival Models  
Video: Survival Function  
Video: Valid Survival Functions  
Video: Collecting Time Data  
Video: When a Stroke is Not Observed  
Video: Heart Attack Data  
Video: Right Censoring  
Video: Estimating the Survival Function  
Video: Died Immediately, or Never Die  
Video: Somewhere in-between  
Ungraded Lab: Counting Patients  
Video: Using Censored Data  
Video: Chain Rule of Conditional Probability  
Video: Deriving Survival  
Video: Calculating Probabilities from the Data  
Video: Comparing Estimates  
Video: Kaplan Meier Estimate  
Ungraded Lab: Kaplan Meier  
Practice Quiz: Survival  

- Programming Assignment: Survival Estimates that Vary with Time


### Week 4. Build a Risk Model Using Linear and Tree-based Models
fit a linear model, and a tree-based risk model on survival data, to customize a risk score for each patient, based on their health profile. The risk score represents the patient’s relative risk of getting a particular disease. You will then evaluate each model’s performance by implementing and using a concordance index that incorporates time to event and censored data.

Video: Hazard Functions  
Video: Hazard  
Video: Survival to Hazard  
Video: Cumulative Hazard  
Ungraded Lab: Categorical Variables  
Video: Individualized Predictions  
Video: Relative Risk  
Video: Ranking Patients by Risk  
Video: Individual vs Baseline Hazard  
Video: Smoker vs Non-smoker  
Video: Effect of Age on Hazard  
Video: Risk Factor Increase Per Unit Increase in a Variable  
Video: Risk Factor Increase or Decrease  
Ungraded Lab: Hazard Function  
Video: Intro to Survival Trees  
Video: Survival Tree  
Video: Nelson Aalen Estimator  
Video: Comparing Risks of Patients  
Video: Mortality Score  
Video: Evaluation of Survival Model  
Video: Permissible and Non-Permissible Pairs  
Video: Possible Permissible Pairs  
Video: Example of Harrell's C-Index  
Video: Example of Concordant Pairs   
Ungraded Lab: Permissible Pairs with Censoring and Time  
 

- Programming Assignment: Cox Proportional Hazards and Random Survival Forests

