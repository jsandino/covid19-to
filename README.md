# Toronto Covid-19 Case Analysis

A simple data science experiment that analyzes Covid-19 data published by Toronto Public Health; details about the data can be found [here](https://open.toronto.ca/dataset/covid-19-cases-in-toronto/)

[Open the colab notebook](https://colab.research.google.com/drive/1QOKytKSQjBsHQQBLlE5FbLAFlaH4Qseg?usp=sharing)

## Background

Given the Covid-19 data collected between January 2020 to February 2024 (for episodes in the metropolitan Toronto region), it would be interesting to use machine learning to gain some intuition about patterns in the data.

## Approach

This experiment uses 4 distinct phases to conduct the analysis:

1. *Ingest* - preliminary setup, where the raw data is loaded and a first round of inspections is performed.
2. *Exploratory Data Analysis (EDA)* - here the data is filtered, transformed and prepared to make it amenable for model construction.
3. *Modeling* - machine learning models are built using the *scikit-learn* library, making observations in the process with the aid of matplotlib
4. *Conclusion* - a brief summary of any interesting discoveries in prior phases

## Modeling

Once the data is prepared, two machine learning approaches are used. First, the K-means *Unsupervised Machine Learning* algorithm is used to produce various alternatives to cluster the data; then a cluster size is selected and used to generate a decision tree, a *Supervised Learning* algorithm, which will help visualize how the data clusters are split.
