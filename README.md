**BreastCancer**

This program is used to detect the breast cancer, based off of data using machine learning algorithm.



**Steps used for Project:**
- Import Libaries
- Load Datasets
- Feature Engineering
- visualization
- split the data set into 75% training and 25% testing
- Creating a Model of Machine Learning Algorithm
- Prediction of Test Datasets
- Checking Accuracy


**Used Libaries**
- numpy 
- pandas
- matplot
- seaborn
- sklearn
 


**Feature Engineering**

**Need of Feature Engineering**
- Preparing the proper input dataset, compatible with the machine learning algorithm requirements.
- Improving the performance of machine learning models.

**List of Feature Engineering Techniques used**
1. Imputation 

    Missing values are one of the most common problems you can encounter when you try to prepare your data for machine learning. 
    The reason for the missing values might be human errors, interruptions in the data flow, privacy concerns, and so on.
    Whatever is the reason, missing values affect the performance of the machine learning models.
2.  Encoding Categorical Features

    It is very common to see categorical features in a dataset. However, our machine learning algorithm can only read numerical values.
    It is essential to encoding categorical features into numerical values. The Used Encoding Categorical Features is LabelEncoder.
3. Scaling

    Standardization is used Scaling in this program.Standardization (or z-score normalization) scales the values while taking into 
    account standard deviation. If the standard deviation of features is different, their range also would differ from each other.
    This reduces the effect of the outliers in the features.


**Algorithm**

- LogisticRegression (Accuracy:-  0.9436619718309859)
- DecisionTreeClassifier(Accuracy:- 1.0)
- RandomForestClassifier (Accuracy:- 0.9953051643192489)

**Conclusion**

By using the RandomForestClassifier for test data, Obtain Accuracy is 0.965034965034965.
    







