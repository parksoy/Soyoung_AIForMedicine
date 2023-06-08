# Soyoung's archive for Coursera AI for Medicine specialization

Do not copy or share as this this repo is only meant to be an archiver for Soyoung's study on coursera AI for Medicine specialization. 
On local, 

`pip install -r requirements_coursera.txt` doesn't work.

On my local conda env is py3p10.

A few more notes on central change:


Especially for C3_W2, 
`pip install nltk, stanfordnlp, PyStanfordDependencies`
`nltk.download()` needed.


# Outline 

## Course 1. [AI for Medical Diagnosis](https://www.coursera.org/learn/ai-for-medical-diagnosis/home/info)

### Week 1. Disease Detection with Computer Vision
practice classifying diseases on chest x-rays using a neural network.
 
Video: Medical Image Diagnosis  
Video: Eye Disease and Cancer Diagnosis  
Ungraded Lab: Data Exploration & Image Pre-Processing  
Video: Building and Training a Model for Medical Diagnosis  
Video: Training, Prediction, and Loss  
Video: Image Classification and Class Imbalance  
Video: Binary Cross Entropy Loss Function  
Video: Impact of Class Imbalance on Loss Calculation  
Ungraded Lab: Counting Labels and Weighted Loss Function  
Video: Resampling to Achieve Balanced Classes  
Video: Multi-Task  
Video: Multi-task Loss, Dataset size, and CNN Architectures  
Ungraded Lab: Densenet  
Video: Working with a Small Training Set  
Video: Generating More Samples  
Video: Model Testing  
Video: Splitting Data by Patient  
Ungraded Lab: Patient Overlap & Data Leakage  
Video: Sampling  
Video: Ground Truth and Consensus Voting  
Video: Additional Medical Testing  
Practice Quiz: Disease Detection with Computer Vision  
 



- Programming Assignment: Chest X-Ray Medical Diagnosis with Deep Learning

### Week 2. Evaluating Models
practice implementing standard evaluation metrics to see how well a model performs in diagnosing diseases.

Video: Sensitivity, Specificity and Evaluation Metrics  
Video: Accuracy in Terms of Conditional Probability  
Video: Sensitivity, Specificity and Prevalence  
Video: PPV, NPV  
Video: Confusion Matrix  
Reading: Calculating PPV in Terms of Sensitivity, Specificity and Prevalence  
Video: ROC Curve and Threshold  
Video: Varying the Threshold  
Ungraded Lab: ROC Curve and Threshold  
Video: Sampling from the Total Population  
Video: Confidence Intervals  
Video: 95% Confidence Interval  
Practice Quiz: Evaluating Machine Learning Models  

- Programming Assignment: Evaluation of Diagnostic Models

### Week 3. Image Segmentation on MRI Images
prepare 3D MRI data, implement an appropriate loss function for image segmentation, and apply a pre-trained U-net model to segment tumor regions in 3D brain MRI images.

Video: Medical Image Segmentation  
Ungraded Lab: Explore MRI Data & Labels  
Video: MRI Data and Image Registration  
Video: Segmentation  
Ungraded Lab: Extract a Sub Section  
Reading: Convolutional Neural networks  
Video: 2D U-Net and 3D U-Net  
Reading: More about U-Net (Optional)  
Ungraded Lab: U-Net Model  
Video: Data Augmentation for Segmentation  
Video: Loss Function for Image Segmentation  
Video: Different Populations and Diagnostic Technology  
Video: External Validation  
Video: Measuring Patient Outcomes  
Practice Quiz: Segmentation on Medical mages  
 

- Programming Assignment: Brain Tumor Auto-Segmentation for Magnetic Resonance Imaging (MRI)




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




## Course 3. [AI for Medical Treatment](https://www.coursera.org/learn/ai-for-medical-treatment/home/info)

### Week 1. Treatment Effect Estimation
How to analyze data from a randomized control trial, interpreting multivariate models, evaluating treatment effect models, and interpreting ML models for treatment effect estimation.

Video: Absolute Risk Reduction  
Video: Randomized Control Trials  
Ungraded Lab: Pandas for a Medical Dataset  
Reading: Clarifications about Upcoming Causal Inference  
Video: Causal Inference  
Video: Average Treatment Effect  
Video: Conditional Average Treatment Effect  
Video: T-Learner  
Video: S-Learner  
Ungraded Lab: Model Training/Tuning Basics with Sklearn  
Video: Evaluate Individualized Treatment Effect  
Video: C-for-benefit  
Video: C-for-benefit Calculation  
Ungraded Lab: Logistic Regression Model Interpretation  
Practice Quiz: Measuring Treatment Effects  

- Programming Assignment: Estimating Treatment Effect Using Machine Learning

### Week 2. Prognosis with Tree-based Models
learn how to extract disease labels from clinical reports, and also question answering with BERT.

Video: Medical Question Answering  
Video: Handling Words with Multiple Meanings  
Video: Define the Answer in a Text  
Ungraded Lab: Cleaning Text  
Video: Automatic Label Extraction for Medical Imaging  
Video: Synonyms for Labels  
Video: Is-a Relationships for Labels  
Video: Presence or Absence of a Disease  
Ungraded Lab: BioC Format and the NegBio Library  
Video: Evaluating Label Extraction  
Video: Precision, Recall and F1 Score  
Video: Evaluating on Multiple Disease Categories  
Ungraded Lab: Preparing Input for Text Classification  
Practice Quiz: Information Extraction with NLP  


- Programming Assignment: Natural Language Entity Extraction

### Week 3. Survival Models and Time
learn how to interpret deep learning models, and also feature importance in machine learning.

Video: Drop Column Method  
Video: Permutation Method  
Ungraded Lab: Permutation Method  
Video: Individual Feature Importance  
Video: Shapley Values  
Video: Combining Importances  
Video: Shapley Values for all Patients  
Video: Interpreting CNN Models  
Ungraded Lab: Introduction to GradCAM (Part 1)  
Video: Localization Maps  
Video: Heat Maps  
Ungraded Lab: GradCAM: Continuation (Part 2)  
Practice Quiz: ML Interpretation   


- Programming Assignment: ML Interpretation
 

