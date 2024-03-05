# Parkinson-s-Disease-Detection

An overview of Parkinson’s disease, it is a brain disorder that causes unintended or uncontrollable movements, such as shaking, stiffness, and difficulty with balance and coordination.
We use Support Machine Vector Classifier (SVM) which is a supervised machine learning algorithm that creates a hyperplane to separate N features, by mapping these features to a multidimensional space. Since PD voice data is not linearly separable, we use an SVM kernel to transform data into higher dimensional space. SVM performs well for PD data due to memory efficiency and support vectors formed from a subset of training data points.

Methodology Overview: 
•	Importing of data of people with Parkinson’s disease and the people without it to find the patterns so as to differentiate the people with and without the disease.
•	Data pre-processing and training and test data separation.
•	Using Support Vector Machine Classifier to train the ML model and to find the efficiency using the Test data.
