This is the repository for Project B.

Project B has two tasks.

Implement Gradient Matching Dataset Distillation
Implement Difficulty-Aligned Trajectory Alignment (for Dataset Distillation)
                                                   
Code for each of the tasks can be found in the respective notebooks.

This project uses the MNIST and MHIST datasets. 

MNIST: 60,000 total samples and 10 classes, with 6000 images per class. 50,000/10,000 train/test split
(equivalent to ~ 83.5%/16.5% ratio).
Link to MNIST dataset: https://www.kaggle.com/datasets/hojjatk/mnist-dataset
                                                   
MHIST: 3152 total samples and 2 classes, with 2162 images in the HP class, and 990 in the SSA class.
i. The HP class has a 1,546/618 train/test split (equivalent to 71.5%/28.5% ratio)
ii. The SSA class has a 631/361 train/test split (equivalent to 63.6%/36.4% ratio).
Link to MHIST dataset: https://bmirds.github.io/MHIST/
                                          

A summary of the performance of the models is below.

Task 1 with MNIST (Benchmark Test Accuracy): 99.5% (Synthetic Set Test Accuracy): 90.63% 

Task 1 with MHIST (Benchmark Test Accuracy): 74.10% (Synthetic Set Test Accuracy): 36.85% 

Task 2 with MNIST (Benchmark Test Accuracy): 99.4% (Synthetic Set Test Accuracy): 21.39% 
                                    
