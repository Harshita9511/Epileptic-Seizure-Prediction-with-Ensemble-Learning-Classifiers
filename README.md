# Epileptic Seizure Prediction with Ensemble Learning Classifiers

<img src="/image.jpg" width="1000" height="300" />
<div align="justify">

In this analysis, the presence of Epileptic Seizure is predicted by employing Support Vector Machine (SVM), Gaussian Naïve Bayes & Decision Tree (DT); Ensemble combination rules i.e., Majority Voting & Weighted Average Voting and Ensemble classifiers i.e., Bagging, Adaptive Boosting, Gradient Boosting XGBoost.<br />
Parameters such as Accuracy, Precision, Recall and F1-score were estimated to analyze the performance and a comparative study of these classifiers was carried out.

## Dataset
Data Source: [Epileptic Seizure Recognition Dataset](https://archive.ics.uci.edu/ml/datasets/Epileptic+Seizure+Recognition#)<br /><br />
**Attribute Information:**<br />
The original dataset from the reference consists of 5 different folders, each with 100 files, with each file representing a single subject/person. Each file is a recording of brain activity for 23.6 seconds. The corresponding time-series is sampled into 4097 data points. Each data point is the value of the EEG recording at a different point in time. So, we have total 500 individuals with each has 4097 data points for 23.5 seconds.<br />
They divided and shuffled every 4097 data points into 23 chunks, each chunk contains 178 data points for 1 second, and each data point is the value of the EEG recording at a different point in time. So now the dataset has 23 x 500 = 11500 pieces of information(row), each information contains 178 data points for 1 second(column), the last column represents the label y {1,2,3,4,5}.<br />

The response variable is y in column 179, the Explanatory variables X1, X2, ..., X178, y contains the category of the 178-dimensional input vector. Specifically, y in {1, 2, 3, 4, 5}:<br />

5 - eyes open, means when they were recording the EEG signal of the brain the patient had their eyes open.<br />
4 - eyes closed, means when they were recording the EEG signal the patient had their eyes closed.<br />
3 – Yes, they identify where the region of the tumor was in the brain and recording the EEG activity from the healthy brain area.<br />
2 - They recorder the EEG from the area where the tumor was located.<br />
1 - Recording of seizure activity.<br />

All subjects falling in classes 2, 3, 4, and 5 are subjects who did not have epileptic seizure. Only subjects in class 1 have epileptic seizure.<br /> 
  
</div>
