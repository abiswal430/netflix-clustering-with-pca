# Netflix Content Analysis and Clustering

## Overview
This project works with a dataset of Netflix movies and TV shows to understand how content is distributed and how it has changed over time. It also uses clustering to group similar content based on selected features.

## Objective
The purpose of this project is to:
- Explore the dataset and understand its structure
- Identify trends in content type, release year, and production
- Study patterns across countries, ratings, and genres
- Apply clustering techniques to group similar content

## Dataset
The dataset contains details about Netflix content, including:
- Type of content (Movie or TV Show)
- Title, director, and cast
- Country of production
- Release year and date added
- Rating and duration
- Genre and description

## Approach

### Data Preparation
Missing values were handled, and categorical data was converted into numerical form where required. The duration column was also processed to extract numeric values.

### Exploratory Data Analysis
Different visualizations were used to understand:
- Distribution of movies and TV shows
- Growth of content over the years
- Country-wise content production
- Popular genres and ratings

### Machine Learning
Relevant features were selected for clustering. The data was scaled, and PCA was applied to reduce complexity. K-Means clustering was then used to group similar content.

### Evaluation
The number of clusters was selected using the Elbow Method, and clustering performance was checked using the Silhouette Score.

## Observations
- Movies are more common than TV shows
- Content increased noticeably in recent years
- A few countries contribute most of the content
- Some genres appear more frequently than others
- Clustering shows patterns based on duration, type, and release year

## Tools Used
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Project Structure
Netflix_Project/
│
├── data/
├── notebooks/
│   ├── Netflix_EDA.ipynb
│   └── Netflix_ML.ipynb
├── requirements.txt
├── README.md
└── LICENSE

## Conclusion
This project shows how data analysis and clustering can be used to understand patterns in a dataset. The results help in identifying similarities in content and can be useful for recommendation systems.

## Author
Arjya Biswal
