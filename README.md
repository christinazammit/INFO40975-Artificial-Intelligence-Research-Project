# INFO40975-Artificial-Intelligence-Research-Project

## Abstract
PyCaret is used to automate workflows in machine learning and utilizes low-code libraries 
to execute a number of processes in just a few lines of code. PyCaret was used to ultimately 
find the answer, “Has the client subscribed to a term deposit?” when exploring the Bank Marketing
Dataset published in UCI Machine Learning Repository. The dataset is multivariate and contains 
real attribute characteristics. Further, it contains 45,211 instances and 17 attributes including
age, job, housing, loan, and the desired target, has the client subscribed to a term deposit? 
The data from this dataset was retrieved using PyCaret and the PyCaret environment was setup 
using PyCaret’s setup() function to automatically infer the attributes’ data types. Next, a 
variety of models were applied to the data and the results were compared to one another on the 
basis of Accuracy, AUC, Recall, Precision, F1, Kappa, and MCC. The results showed that Light 
Gradient Boosting Machine (LightGBM) produced the highest accuracy of 90.85%. After tuning the 
model using tune_model(), which tunes the hyperparameters, the mean accuracy of the LightGBM 
model is 90.68%. Some of the best performing hyperparameters for the LightGBM model was 
bagging_fraction=0.6, bagging_freq=2, boosting_type=’gbdt’, and reg_alpha=2, to name a few. 
Before the model was finalized, the test/hold-out set was predicted using predict_model() 
and the evaluation metrics were evaluated. After prediction, the accuracy of the LightGBM model 
was 90.7%.

Click [here](https://colab.research.google.com/drive/18BkZvbtPc_VNEg7HQzv8NZQ3eoKLGaKe?usp=sharing) to visit the Jupyter Notebook

Click [here] for a video demonstration of the project
