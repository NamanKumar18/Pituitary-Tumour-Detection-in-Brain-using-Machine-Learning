# Pituitary Tumour Detection in Brain using Machine Learning
---

## **Use Case**:
#### Brain Tumours are a critical condition which requires early detection and treatment for the patients to survive and ensure proper counter measures, however it becomes almost impossible to detect them at early stage. Hence we propose a prototype which can help identify patients with potential pituitary tumours using brain MRI scans. This can be of huge help in the medical field in assisting doctors.

### This is a Python script that trains four classifiers to classify brain tumor MRI images into two classes: no_tumor and pituitary_tumor. The code does the following:

- Imports required modules for data preprocessing, visualization, and modeling.

- Collects the data from the specified path, resizes each image to (200,200), converts the images into numpy arrays, and labels each array based on the folder name.

- Splits the dataset into training and testing sets using the train_test_split method.

- Scales the pixel values of the images between 0 and 1.

- Uses Principal Component Analysis (PCA) to reduce the number of attributes of the dataset.

- Trains four classifiers: Logistic Regression, Support Vector Machines (SVM), Random Forest, and K-Nearest Neighbors Classifier (KNN).

- Evaluates the performance of each classifier on both the training and testing sets.

- Plots the training and testing scores of each classifier using a bar chart.

- Returns the best performing classifier based on the testing score.

### Overall, this code aims to classify brain tumor MRI images using four different classifiers and select the best classifier based on its performance on the testing set.

---
The following concludes our project submission for OPERATING SYSTEMS to Ms. Somiya Rani.
---
|Name|Roll No.|
--
|Aayush Kumar Singh|2020UEA6619|
|Harsh Nagar|2020UEA6588|
|Dhruv|2020UEA6564|
|Naman|2020UEA6598|
