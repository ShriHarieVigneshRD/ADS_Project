# Analysis of Chicago Crime Data

## Overview
This project analyzes Chicago Crime Data using both descriptive and predictive methods to visualize crime trends across time, location, and type. The study also applies frequent itemset mining techniques to reveal associations between crime types.

## Dataset
The dataset used for this analysis can be found at: [Chicago Analysis of Crime Data Dashboard](https://www.kaggle.com/datasets/elijahtoumoua/chicago-analysis-of-crime-data-dashboard)

## Project Structure
The analysis is divided into two main components:

### 1. Descriptive Analysis
- **Data Visualization**:
  - Time-based patterns (yearly and monthly trends)
  - Location-based patterns (scatter plots for crime hotspots)
  - Crime type distribution (bar charts and pie charts)
- **Data Preprocessing**:
  - Handling missing values to maintain data integrity

### 2. Predictive Analysis
- **Association Rule Mining**:
  - Frequent Itemset Mining (finding common crime associations)
  - Association Rules (understanding crime correlations)
- **Classification Models**:
  - Decision Tree Classifier
  - Naive Bayes Classifier
  - Support Vector Classifier (SVC)
- **Clustering Algorithms**:
  - K-Means Clustering
  - K-Medoids Clustering
  - DBSCAN Clustering
  - HDBSCAN Clustering
- **Big Data Processing with PySpark**:
  - FP-Growth Algorithm
  - Naive Bayes Classification
  - AGNES Clustering

## Key Findings
### Descriptive Analysis
- **Crime Trends**: Crimes have shown a steady decline from 2000 to 2022, with a significant drop after 2019.
- **Crime Hotspots**: Central Chicago experiences a higher concentration of crimes.
- **Crime Severity**: Severe crimes make up the largest proportion, followed by moderate and minor crimes.

### Predictive Analysis
- **Association Rule Mining**: Frequent crime combinations were identified, highlighting relationships between different crime types.
- **Classification Models**: Decision trees and SVC provided high accuracy in predicting crime types based on location and time.
- **Clustering**: Crime hotspots were identified using clustering techniques, helping in better resource allocation for law enforcement.

## Technologies Used
- **Python**: Pandas, Matplotlib, Seaborn, Scikit-learn
- **Machine Learning Algorithms**: Apriori, FP-Growth, Decision Trees, SVC
- **Clustering Techniques**: K-Means, DBSCAN, HDBSCAN
- **Big Data Processing**: PySpark for large-scale analysis


## Results and Visualizations
- All generated plots and results are saved in the `output/` directory.
- Detailed inferences from visualizations and models can be found in the report.

## Future Improvements
- Expand analysis to include real-time crime data.
- Implement deep learning models for crime prediction.
- Improve clustering accuracy using advanced spatial analysis techniques.



