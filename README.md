# 🧠 Technical Challenge: Building an End-to-End Data Pipeline for an iOS App
## Overview
You're tasked with contributing to the development of a system that captures sensor data from an iOS device, processes it through a cloud function, and utilizes machine learning to derive insights. This challenge is divided into three distinct tracks. You may choose the one that aligns best with your interests and skills.

## 📦 General Guidelines
Timeline: You have up to 7 days to do this, but don't dedicate more than 3 days. Make sure you time manage your approach into small milesones to make sure you can deliver somethign functional without over extending

### Collaboration: This is an individual challenge; collaboration is not permitted.

### Evaluation Criteria:

* Code quality and organization.
* Creativity and problem-solving approach.
* Clarity and completeness of documentation.
* Functionality and adherence to requirements.
* Ability to explain and justify your implementation choices.

### Extra brownie points:
* You wrote tests
* Code is structured following SOLID principles
* Diagrams of the approach

## 🧾 Submission Instructions
You can submit the code as your preference, ie: github repo, zip, etc. Email the link or file to your point of contact
Make sure to add a document explaining your thoughts, approaches, etc

## Note on AI Usage:
You are encouraged to utilize AI tools (e.g., ChatGPT, GitHub Copilot) to assist in your development process. However, it's imperative that you fully understand and can articulate all aspects of your implementation. During the evaluation, you may be asked to explain your code, design decisions, and the rationale behind them.

# Tracks
## 📱 Track 1: iOS App Development
### Objective:
Develop an iOS application that collects sensor data and sends it to a backend service.

### Requirements:

* Utilize Swift for app development
* Capture data from at least one sensor (e.g., accelerometer, GPS, gyroscope).
* Format and send the data to a mock backend endpoint, it can be just a class that receives the data
* Implement error handling and data validation.
* Provide a user-friendly interface to start/stop data collection and view status.

## ☁️ Track 2: Data Normalization Service
### Objective:
Create a cloud function that receives raw sensor data and normalizes it for machine learning processing.

### Requirements:

* Develop the function using a language of your choice (e.g., Python, Node.js).
* Implement data validation and error handling.
* Normalize data (e.g., scaling, encoding) to prepare for ML models.
* Store the processed data in a database or cloud storage.

## 🤖 Track 3: Machine Learning Model Development
### Objective:
Develop a machine learning model that analyzes normalized sensor data to detect patterns or make predictions.

### Requirements:

* Use Python with libraries like scikit-learn, TensorFlow, or PyTorch.
* Train the model on provided or simulated normalized data.
* Evaluate model performance using appropriate metrics.
* Save the trained model in a format suitable for deployment (e.g., Core ML for iOS integration).



