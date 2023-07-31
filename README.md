# TrustVerity - Verifying App Authenticity through Sentiment Analysis
TrustVerity is a sentiment analysis project that aims to verify the authenticity of mobile apps by analyzing user reviews. By leveraging natural language processing techniques, this project provides insights into the sentiments expressed in app reviews, helping users distinguish between safe and potentially fraudulent apps.

## Overview
The project consists of the following key components:

### Data Collection: We utilize the Google Play Scraper to collect user reviews from various mobile apps. The collected data is then stored in CSV files for further analysis.

### App Classification: Based on app ratings, the last update date, and user reviews, the apps are categorized as "fraud" or "safe." This classification is crucial for targeted sentiment analysis.

### Sentiment Analysis: We perform sentiment analysis on the user reviews using a pre-trained sentiment analysis model. This step helps us determine the sentiment (positive, negative, neutral) expressed in each review.

### Results Storage: The sentiment analysis results are stored alongside the app reviews in the CSV files. This organized storage allows for easy access and further analysis.

### Overall Sentiment Prediction: By analyzing the sentiment distribution from the reviews, we make an overall sentiment prediction for each app. This prediction aids in understanding the app's sentiment as a whole.

## Getting Started
To use TrustVerity, follow these steps:

Clone the repository to your local machine.

Install the required dependencies using the provided requirements.txt file.

Run the data collection script to gather app reviews from the Google Play Store.

Classify the apps based on ratings, last update date, and reviews to distinguish between "fraud" and "safe" apps.

Conduct sentiment analysis on the reviews using the pre-trained sentiment analysis model.

View the sentiment analysis results and overall app sentiments in the generated CSV files.

## Dependencies
1) Python: TrustVerity is primarily developed using Python, and you will need a compatible version of Python installed on your system to execute the scripts and run the web application.

2) Google Play Scraper: TrustVerity utilizes the Google Play Scraper library to scrape mobile app reviews from the Google Play Store. Install this library to collect the necessary data.

3) Plotly Express: This library is used for data visualization in TrustVerity. Ensure you have Plotly Express installed to visualize the analysis results effectively.

4) Pandas: Pandas is essential for data manipulation and analysis in TrustVerity. Make sure you have Pandas installed to handle data efficiently.

5) Flask: TrustVerity uses Flask to create and run the web application. Install Flask to deploy and interact with the web interface.

6) HTML/CSS: HTML and CSS are utilized in TrustVerity to render the prediction page and create an interactive user interface. Make sure to have these technologies in place to view and interact with the results.

7) Transformers library: This library is required for sentiment analysis in TrustVerity. Install Transformers to use pre-trained models for interpreting app review sentiments.

8) NLTK library: TrustVerity uses NLTK for text processing. Install the NLTK library to handle text data effectively.

9) JavaScript: JavaScript is employed to incorporate interactive elements and enhance user experience in the web application. Ensure JavaScript is properly integrated into your web application for dynamic rendering and interactivity.

## Contribution
We welcome contributions to enhance TrustVerity. If you find any issues or have suggestions for improvement, please open an issue or submit a pull request. Let's work together to make app verification more reliable and secure!
