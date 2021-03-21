# Introduction
This repository contains my submission to the Kaggle Cassava Leaf Disease Classification Challenge. Cassava is the second-largest provider of carbohydrates in Africa but viral diseases are major sources of poor yields. The goal of the challenge is to help cassava farmers diagnose their crops based on mobile taken images

Since this is an image classification problem, I opted to use the ResNet50 model and further train it with the cassava data. The code is broken down into 2 main files: training file and the submission file

# Solution and Results
This solution is implemented using Keras. It was based on the RestNet50 model trained on the ImageNet data set and further trained using the cassava data set.

This model garnered a private score of 0.7336 and a public score of 0.7230.
