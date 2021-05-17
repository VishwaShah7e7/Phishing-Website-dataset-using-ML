# Phishing-Website-dataset-using-MachineLearning


**Problem**

Phishing websites disguise themselves as trustworthy websites in order to gain the trust of their victims, and malicious parties use them to obtain sensitive information from their victims.Attackers change the subdomain and file path(if it contains in the URL) or they make a  typo mistake to look like a legitimate website. So to identify phishing websites we need to break down the URL to look at what each part of the URL contains.

**Solution**

To detect the phishing website by using website URL features like top level domain, filepath , domain activation time etc.

**Approach**

- We broke down the URL into multiple parts: protocol, domain name, directory name, file name and other URL parameters, then found the relation of the features to the target variable.
- We have chosen important features by visualizing the features using correlation heat map, using mutual information to the target variable.
- After choosing the important features from the dataset we have applied various ML models like Regression, Support Vector Machine, KNN, Random Forest, Stacking and XGboost. 
- We have compared the accuracy, precision and recall of the above mentioned models along with the time complexity of the model.

**Dataset used**
https://data.mendeley.com/datasets/72ptz43s9v/1






