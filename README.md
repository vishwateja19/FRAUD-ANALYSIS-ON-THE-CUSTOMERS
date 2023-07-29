
## FRAUD ANALYSIS ON THE CUSTOMERS:

In this Repo , I have done a Project on machine learning classification problem statement Which requires a Huge dataset where I got it from 3rd part websites and don't worry I want to share the dataset with you and you can get it from here:


![App Screenshot](https://camo.githubusercontent.com/80e590adb56e379d95215f6212c0bcee9408dfe043836bb09d8f0a9652a11bcd/68747470733a2f2f69302e77702e636f6d2f646174616173706972616e742e636f6d2f77702d636f6e74656e742f75706c6f6164732f323032302f30392f312d4372656469742d636172642d66726175642d646574656374696f6e2d776974682d636c617373696669636174696f6e2d616c676f726974686d732e706e673f773d3735302673736c3d31)


Using Pandas library I loaded the dataset and also check the complete information about the dataset using the same library. since the data is having lot of Null values I am going to take help of statistics concept to clean the data and if my approach was not a good way for doing this Project Please let know. But while focusing on Missing values I got it know Last 2 rows are completely NAN so I removed the last 2 Rows.

yah After removing last 2 rows the data becomes quite good where only 2 columns having null values and remaining things are solved:





## I am following Machine Learning pipeline for developing this project :

       - PipeLine of Machine Learning Project:
       - Collect the data
       - check the data information
       - split the data
       - training operations should be done on test data [Just Keep in Mind]
       - Handle Missing values if There
       - EDA Part [Exploratory Data Analysis]
       - Checking Normal Distribution
       - Checking Outliers
       - Handling them
       - Handle Cateogorical data
       - Transformation Techniques
       - select best features for both numerical and categorical data
       - Model developement
       - check validation
       - Evaluate model
       - check AUC and ROC For selecting Best Model
       - Hyperparameter tuning on the top of the best model
      
## why spliting the data:
If we divide the data after feature engineering part the std[standard deviation and variance] will be completely different for both train and test this leads to data leakage, so to overcome this I am splitting the data and applying the operations on train same result saving it for test:
## Handle Missing values:
for Handle Missing values we have used mean median and mode concept where its working really fine and when coming to Outliers I applied a Techniques called std and iqr since it really works fine the worst feature converts into proper feature:

![download (2)](https://github.com/vishwateja19/FRAUD-ANALYSIS-ON-THE-CUSTOMERS-/assets/114558376/00743f53-e809-423e-9671-bb1c4679a637)


Meanwhile while working with feature engineering part I am taking the help of sklearn and fearture engine frameworks for better EDA and model developement part:

Techniques done using sklearn and feature engine :
          
          - Variable Transformation
          - Outliers
          - data scaling concepts 

## Since EDA part Feature engineerig part is to high I am not going to explain each line of code here You can check it from the above coding file:


## Feature selection:
![App Screenshot](https://camo.githubusercontent.com/b9bb40e05e6523b03cbcb3a677da4c6bd878cf8280d8f992e7eb05f22b2dd8ce/68747470733a2f2f69302e77702e636f6d2f6e657074756e652e61692f77702d636f6e74656e742f75706c6f6164732f323032322f31302f666561747572652d73656c656374696f6e2d6d6574686f64732d312e706e673f726573697a653d3736372532433435322673736c3d31)

As mentioned in the above Image there are multiple methods for Analysis of feature selcetion but for My data using sklearn and feature engine I have gone with correlation and filter methods for numerical data since some columns selected as best remaining things I removed from the data: using correlation even My threshold value is to high 0.85 but no feature is passing or crossing the threshold value so correlation didn't select best features. using Hypothesis testing I got best features with p_value < 0.5 concept>


## Finally entire data is set ready for Model developement Purpose:

since the data is not balanced using Upsamping and down sampling concepts I Handle them.

Know I selected KNN , naive bayes , Logistic Regression , Decision Tree and Random Forest for Model developement:

since after training the model I got the results of :

              - KNN Accuracy : 0.8703838383838384
              - NB Accuracy  : 0.6992929292929293
              - LR Accuracy  : 0.7377373737373737
              - DT Accuracy  : 0.707939393939394
              - RF Accuracy  : 0.690949494949495

since almost the results are very close to each other I stuck around to select the best model: No worries I am having AUC and ROC concept so I find out FPR and TPR using Grapical represntation and selected best model which is Logistic Regression:


![download (3)](https://github.com/vishwateja19/FRAUD-ANALYSIS-ON-THE-CUSTOMERS-/assets/114558376/ff5f793c-1035-41f6-b4b4-383199506206)



Finally It takes lot of time for Data Analysis and model developement part but following ML pipeline really gives me perfect way for doing an End-to-End peoject:

Entire code and hidden information You can get it from the above coding file:
## 🛠 Skills

1.Python 

2.Machine learning 
    
3.Statistics

4.Mathematics
    
5.Numpy 
    
6.Neural Networks
## 🔗 Links:
https://www.linkedin.com/in/vishwateja-bandi-32910a209/
