Employee-Check-in-System

Problem Statement:
As the Security Analyst at Stark Industries, the task is to develop a contactless employee check-in system. The current system relies on physical keycards for entry, which presents limitations. The proposed solution involves utilizing employees' smartphones and machine learning techniques, specifically gait analysis, to create a seamless and secure entry system.

Dataset has axis of 30 employees different body parts while they were doing their casual daily activities through the Gyroscope and Accelerometer that are present in their smartphones. Here the coordinates will be varying from every other individual as everyone has a different style of standing, walking, sitting, laying. Also, the body measurements of everyone are also different so by considering an individual’s body axis on how they enter the offices can help us to build a security system that is fast and secure.

Attribute Information: For each record in the dataset, it is provided
Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
Triaxial Angular velocity from the gyroscope.
A 561-feature vector with time and frequency domain variables.Its activity label.
An identifier of the subject who carried out the experiment.

we chose logistic regression because of its high dimensional capabilities, scalability.
The dataset has 561 features, Logistic Regression can efficiently handle this number of features.
The trained model then gave a model score of how it performed on the training dataset.
We run the model on the testing data and got a prediction score. A classification report for the model was depicted. 
The analysis was summed up by a confusion matrix to evaluate the final performance of the algorithm.

Our model exhibits exceptional performance across all activities, boasting high precision, recall, and F1-scores. While there are slight dips in metrics for Activities 4 and 5, indicating minor misclassifications, the overall accuracy of 98% underscores the robustness of our model in accurately recognizing and classifying various activities based on the dataset. 
