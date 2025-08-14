Market Segmentation Analysis of McDonald's Customer Perceptions

This project performs a comprehensive market segmentation analysis on a dataset of customer perceptions of McDonald's. The primary goal is to identify distinct customer segments using the K-Means clustering algorithm and to profile them based on their attitudes and demographic data.

The analysis is conducted in a Jupyter Notebook (.ipynb) and follows a structured, step-by-step workflow from data exploration to final strategic evaluation.

Key Features
Exploratory Data Analysis (EDA): Uses Principal Component Analysis (PCA) to create a perceptual map of brand attributes.

K-Means Clustering: Employs the elbow method to determine the optimal number of segments and groups customers accordingly.

Segment Profiling: Creates detailed profiles for each segment using visualizations like profile plots, mosaic plots, and boxplots.

Predictive Modeling: Builds a simple classification tree to identify the key characteristics of a specific target segment.

Strategic Evaluation: Summarizes the findings in a final segment evaluation plot, ideal for business presentations.

Dataset
This project uses the mcdonalds.csv dataset, which contains survey responses from 1,453 consumers. The key variables include:

Perceptual Attributes: 11 binary (Yes/No) attributes like tasty, cheap, healthy, etc.

Descriptor Variables: Like rating (from "I hate it!" to "I love it!"), Age, VisitFrequency, and Gender.

Note: For the notebook to run correctly, the mcdonalds.csv file must be in the same directory.

Installation
This project uses standard Python data science libraries. To install all the necessary dependencies, run the following command in your terminal or in a Jupyter cell:

Bash

pip install pandas numpy scikit-learn matplotlib seaborn statsmodels
Usage
Ensure all required libraries are installed (see above).

Make sure the mcdonalds.csv data file is in the same folder as the notebook.

Open the Jupyter Notebook file (.ipynb).

Run the cells sequentially from top to bottom.

Project Workflow
The analysis is broken down into the following key steps within the notebook:

Data Loading and Preprocessing: The raw data is loaded, and perceptual attributes are converted to a numeric format.

Exploratory Analysis with PCA: A perceptual map is generated to visualize the relationships between brand attributes.

Determining Segment Number: A scree plot is used to identify the optimal number of segments (determined to be 4).

Executing K-Means: The final 4-segment model is created.

Profiling and Describing Segments: Each segment is analyzed in detail using their perceptions, 'Like' ratings, age, and gender.

Predictive Modeling: A classification tree is built to understand the drivers of membership in a specific segment.

Final Evaluation: A bubble chart is created to provide a high-level strategic overview of the segments.

Summary of Segments Found
The analysis identified four distinct customer segments:

The Fans: A younger, predominantly female group that loves McDonald's, finds it tasty and convenient, and visits frequently.

The Haters: A group that strongly dislikes McDonald's, perceiving it as disgusting and expensive, and rarely visits.

The Critics: An older, predominantly male segment that finds McDonald's expensive and unhealthy but visits occasionally.

The Pragmatists: A segment that doesn't love or hate the brand but finds it cheap and convenient.

Contact - chandr4243@gmai.com
Created by Chandrabhushan Upadhyay - feel free to reach out!