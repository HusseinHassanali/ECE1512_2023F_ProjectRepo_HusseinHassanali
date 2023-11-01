This is the repository for Project A.

Project A has two tasks. 
1. Implement KD and XAI on the MNIST Dataset
2. Implement KD on the MHIST Dataset

Code for each of the tasks can be found in the respective notebooks. 

A summary of the performance of the models is below. 

Task 1 (Accuracy Metric):
Teacher: 98.82%
Student with KD: 98.27%
Student with no KD: 97.33%

Task 2 (AUC-PR Metric):
Teacher: 71.06%
Student with KD, no ImageNet Weights: 73.63%
Student with no KD, with ImageNet Weignts: 74.62%
Student with KD, no Data Augmentation: 85.26%
Student with KD, with Data Augmentation: 36.85%
