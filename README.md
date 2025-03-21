# SMS-SPAM
SMS SPAM Detection using ML algoritms
Project Overview
This project aims to develop a machine learning model to classify SMS messages as either spam or non-spam (ham). The model is trained on a labeled dataset of messages and is expected to accurately distinguish between spam and legitimate messages.
GitHub Repository Requirements
Create a dedicated GitHub repository for this task.
Include this README file to describe the project.
Ensure the repository has clean, well-structured, and well-commented code.
Dataset
File Name: spam.csv
Description: The dataset consists of SMS messages labeled as spam or ham.
Columns:
label: Indicates whether the message is spam or ham.
message: The actual SMS text content.
Preprocessing Steps:
Remove unnecessary columns (if any).
Convert labels ('spam', 'ham') into binary values (1 for spam, 0 for ham).
Perform text preprocessing (lowercasing, removing special characters, stopwords, and tokenization).
