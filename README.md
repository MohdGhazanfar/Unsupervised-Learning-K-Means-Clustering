# Unsupervised-Learning-K-Means-Clustering

Customer Segmentation using K-means Clustering
This code is an example of customer segmentation using K-means clustering. The purpose of this project is to demonstrate how to use K-means clustering to group customers based on their similarities in demographic or behavioral features, and to provide insights into customer behavior, preferences, or needs, which can be used for targeted marketing, personalized recommendations, or product development.

Dataset:

The dataset contains customer information, including demographic and behavioral features, such as gender, profession, Spending_Score, Family_Size etc.
The dataset is cleaned by removing duplicates and missing values before being used for analysis.

Prerequisites:

This code requires the following Python libraries to be installed:

    • pandas
    • numpy
    • scikit-learn
    • matplotlib
    
In addition, the following modules are also imported from these libraries:

    • LabelEncoder from sklearn.preprocessing
    • StandardScaler from sklearn.preprocessing
    • SelectKBest and f_classif from sklearn.feature_selection
    • KMeans from sklearn.cluster

These libraries can be installed using pip or conda package managers.

Usage:

To use this code, simply clone the repository and run the K -Mean Clustering.ipynb script. The script will perform the following steps:

    • Load the customer segmentation dataset from the CSV file.
    • Clean the data by removing duplicates and missing values.
    • Encode categorical features using LabelEncoder.
    • Scale the features using StandardScaler.
    • Select relevant features using SelectKBest.
    • Apply K-means clustering with various k values and choose the optimal number of clusters based on the elbow point in the plot of intra-cluster variance.
    • Assign cluster labels to the data points.
    • Plot the data points with their assigned cluster labels using matplotlib.
    • The output of the script is a plot of the data points colored by their assigned cluster labels.

Credits:

The customer segmentation dataset used in this project is obtained from Kaggle. 
