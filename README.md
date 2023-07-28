# Phishing URL Detector Website using ML Models

![Project Logo](url_to_logo.png)

This GitHub repository contains the code and resources for a Phishing URL Detector website, which utilizes machine learning models to predict whether a given URL is a phishing or legitimate website. The process involves acquiring a raw dataset from the Kaggle repository, preprocessing the data to improve its reliability and usefulness for machine learning algorithms.

## Project Overview

The primary objective of this project is to create an interactive and responsive website that allows users to detect whether a website URL is legitimate or potentially a phishing attempt. The website utilizes a variety of machine learning algorithms, such as Logistic Regression, K-Nearest Neighbors, Support Vector Machine, Naive Bayes Classifier, Decision Tree, Random Forest, Gradient Boosting Classifier, CatBoost Classifier, XGBoost Classifier, and Multi-layer Perceptron.

## Architecture

The proposed system follows the architecture shown below:

![Architecture](url_to_architecture_diagram.png)

## Data Preprocessing

To ensure the machine learning algorithms can learn effectively from the dataset, the raw data undergoes data cleansing. Junk, missing, or invalid values are removed from the dataset to improve its quality and facilitate better results from the machine learning models.

## Feature Extraction

The project utilizes four types of feature extraction techniques:

1. Address Bar Based: Extracting features related to the URL's address bar.
2. Abnormal Based: Identifying abnormal patterns in the URL.
3. HTML and JavaScript Based: Analyzing features derived from the HTML and JavaScript code of the webpage.
4. Domain Based: Extracting features related to the domain of the URL.

## Machine Learning Models

Several versatile machine learning algorithms are employed to build models for predicting whether a URL is phishing or legitimate. These algorithms include Logistic Regression, K-Nearest Neighbors, Support Vector Machine, Naive Bayes Classifier, Decision Tree, Random Forest, Gradient Boosting Classifier, CatBoost Classifier, XGBoost Classifier, and Multi-layer Perceptron. The models are compared based on their accuracy, and the most effective algorithm is selected as the best model for the detection process.

## Website Development

The project includes a dedicated website, developed using HTML, CSS, and JavaScript. The website is designed to be user-friendly, interactive, and responsive. Its structure and layout are created with HTML, while CSS adds visual effects to enhance user experience. JavaScript is used to implement dynamic features, making it easy for users to enter URLs and receive immediate predictions.

## Getting Started

To access the website and explore the machine learning models, follow these steps:

1. Clone the repository to your local machine using the following command:
   ```
   git clone https://github.com/your-username/phishing-url-detector.git
   ```

2. Navigate to the website directory and open the `index.html` file in your web browser.

3. Enter the URL you wish to check for phishing detection.

4. The website will provide a prediction of whether the URL is legitimate or a potential phishing attempt, based on the selected machine learning model.
