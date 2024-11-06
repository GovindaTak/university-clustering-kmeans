# university-clustering-kmeans
A K-Means clustering project for categorizing universities into Private and Public groups using unsupervised learning. This project involves clustering analysis, model evaluation, and comparison with actual labels to gauge clustering effectiveness.

# University Clustering Project with K-Means

This project leverages the K-Means clustering algorithm to categorize universities into two groups: Private and Public. It serves as an example of how clustering can be applied to data without labels, though in this case, we have labels available to evaluate the performance of our clustering.

## Project Overview
K-Means clustering is an unsupervised machine learning algorithm that attempts to categorize data points into clusters based on feature similarity. This project explores the effectiveness of clustering on university data, which includes various characteristics of universities.

## Problem Statement
The aim is to categorize universities into two groups (Private and Public) without using the labels during clustering, and then assess the performance by comparing the predicted clusters with the actual labels.

## Dataset
The dataset consists of 777 observations with 18 variables:
- **Private**: Indicates if the university is private or public (label, not used in clustering).
- **Apps**: Number of applications received.
- **Accept**: Number of applications accepted.
- **Enroll**: Number of new students enrolled.
- **Top10perc**: Percentage of new students from top 10% of high school class.
- **Top25perc**: Percentage of new students from top 25% of high school class.
- **F.Undergrad**: Number of full-time undergraduates.
- **P.Undergrad**: Number of part-time undergraduates.
- **Outstate**: Out-of-state tuition fees.
- **Room.Board**: Room and board costs.
- **Books**: Estimated book costs.
- **Personal**: Estimated personal spending.
- **PhD**: Percentage of faculty with Ph.D.s.
- **Terminal**: Percentage of faculty with a terminal degree.
- **S.F.Ratio**: Student/faculty ratio.
- **perc.alumni**: Percentage of alumni who donate.
- **Expend**: Instructional expenditure per student.
- **Grad.Rate**: Graduation rate.

## Project Structure
- **Data Exploration**: Understanding the data through visualization and descriptive statistics.
- **Preprocessing**: Scaling features and preparing data for clustering.
- **Modeling**: Applying K-Means clustering algorithm.
- **Evaluation**: Comparing the resulting clusters with the actual labels for evaluation.

## Results
- **Confusion Matrix** and **Classification Report** are used for evaluation, though typically not a part of unsupervised learning. They are included to analyze the effectiveness of clustering.

## Requirements
- Python 3.x
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Usage
Clone the repository and execute the Jupyter Notebook file to see the full project workflow and results.

## Acknowledgments
Special thanks to Sreejith, Rajat, and Sanjay for their mentorship, and the ATMECS team for their support throughout this project.
