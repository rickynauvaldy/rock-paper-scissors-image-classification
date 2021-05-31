# Rock, Paper, Scissors Image Classification

This notebook provides a program to do image classification of rock, paper, scissors images using Python, Google Colab, CNN, and TensorFlow.

This project is made as the submission of Dicoding class "Belajar Machine Learning untuk Pemula" (Learning Machine Learning for Beginners) which can be accessed here https://www.dicoding.com/academies/184.

# Submission Criteria
Some of the criteria that should be in this project:
- Using rockpaperscissors dataset (like the one here https://www.kaggle.com/drgfreeman/rockpaperscissors)
- Split into train and validation set (60:40)
- Implement image augmentation
- Using Image Data Generator
- Using Sequential model
- Training under 30 mins
- Done in Google Colab
- Reach accuracy of minimum 85%
- Ability to predict uploaded image in Colab

# Flow
1. Preparation
2. Get Data
3. Image Data Generator
4. Split Train Data
5. Build Sequential Model
6. Compile and fit
7. Upload test image

# Image Processing
- Input parameters used the one from the Dicoding Module: 
- https://www.dicoding.com/academies/184/tutorials/8527
- We do the train-test split (train-validation) in 60:40 proportion using the parameter "validation_split" of 0.4

# Notes
- There are no other additional exploration beside of the example from Dicoding module. It might be good to explore.
- Even though the accuracy might give >90%, in some cases the uploaded image will be classified in two classes. I assume there still need more data to be learned by the machine, with different environment (not only green as shown in the dataset)
- I would like to thank Lintasarta and Dicoding to give me the scholarship of Lintasarta DigiSchool 2021 (https://lintasartadigischool.dicoding.com/) so that I am able to finish this course

# Contact
For further information, you might want to reach me to ricky.nauvaldy@gmail.com