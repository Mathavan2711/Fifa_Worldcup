# PRCP-1004: FIFA 20 Player Analysis & Clustering

## Project Overview
This project analyzes the FIFA 20 player dataset to explore football player attributes, identify patterns in player performance, and group players into meaningful clusters based on their skill profiles.

The notebook focuses on:
- Exploratory Data Analysis (EDA)
- Data cleaning and feature engineering
- Clustering using unsupervised learning techniques
- Comparing multiple clustering models
- Answering football-related business questions from the dataset

## Objective
The main goal is to identify different types of football players based on playing attributes rather than using raw ratings like Overall or Potential as clustering inputs. Instead, clustering is performed on skill-based attributes to reveal playing styles and performance patterns.

## Dataset
- File: `players_20.csv`
- Source: FIFA 20 player dataset
- Records: All players available in the FIFA 20 data file

## Key Questions Explored
- Which countries produce the most footballers?
- How does player overall rating change with age?
- At what age do players stop improving?
- Which attacking position earns the highest wages?
- What player clusters emerge from the data?

## Workflow
1. Load the dataset
2. Understand column structure and missing values
3. Clean the dataset and handle duplicate records
4. Convert and engineer key features
5. Explore distributions and business insights
6. Prepare clustering features
7. Apply multiple clustering algorithms
8. Evaluate model performance using clustering metrics
9. Compare models and recommend the best approach

## Clustering Models Used
- K-Means
- Agglomerative Clustering
- DBSCAN
- Gaussian Mixture Model

## Evaluation Metrics
- Silhouette Score
- Davies-Bouldin Index
- Calinski-Harabasz Score

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- SciPy

## File Structure
- `PRCP-1004-Fifa20-Analysis (1).ipynb` — main analysis notebook
- `players_20.csv` — FIFA 20 dataset
- `Readme.md` — project documentation

## Notes
- `Overall` and `Potential` are not used as direct clustering inputs.
- They are used mainly for interpretation and business analysis.
- Clustering is based on movement, attacking, skill, defending, and physical attributes.

## Project Outcome
This project provides a practical example of how unsupervised learning can be used in sports analytics to group football players according to their playing profile and identify patterns hidden in performance data.

## Author
Mathavan
