# SIADS_696_Milestone_II
Predicting PGA Tour Tournament Results and Player Clustering by Play Style

This project applies supervised and unsupervised machine learning methods to PGA Tour data (2015–2022) to predict player tournament outcomes and identify groups of golfers with similar playing styles.

Using performance statistics such as strokes gained metrics, we trained several models — including multinomial logistic regression, random forest, LightGBM, and a neural network — to predict player finishing positions. While results showed only modest predictive power (slightly better than random), they provided meaningful insights into feature importance and model limitations.

We also performed dimensionality reduction (PCA, t-SNE) and K-means clustering to group golfers based on strokes gained data. These clusters effectively distinguished top performers and revealed stylistic similarities among players.

Dataset: PGA Tour Golf Data (2015–2022) on Kaggle

Authors: Benjamin Wilson, Peter Sklamberg, James Doherty
Course: University of Michigan – SIADS 696 (Milestone II)
