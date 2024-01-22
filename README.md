# Netflix Movies and TV Shows: Clustering

![GitHib Logo](https://github.com/Bhushan0097/03.CAPSTONE.ML.Classification--Email-Campaign-Effectiveness-Prediction/blob/main/Header.jpg)

## Overview
This repository contains the code and resources for a supervised machine learning project aimed at predicting whether a deliverd email will be read , acknowledged or ignored. The dataset used is `NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv`.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [ML Model Training and Evaluation](#mL-Model-training-and-evaluation)



## Introduction

This repository is dedicated to the exploration and clustering of Netflix content based on various attributes like genre, release year, and ratings. By leveraging unsupervised learning techniques, we aim to uncover hidden patterns and groupings within the vast Netflix library. This project offers insights into content categorization, allowing for personalized recommendations and a deeper understanding of the diverse range of movies and TV shows available. Dive into our documentation to explore the clustering methodology, discover valuable insights, and contribute to the enrichment of content analysis on Netflix.

## Dataset

The dataset `NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv` is included in the  📁 `data` directory. 

The `NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv` file contains the following columns:



- **type** Indicates whether the entry is a movie or a TV show
- **title** The title of the movie or TV show
- **director** The director(s) of the movie or TV show.
- **cast** The main cast or actors involved in the movie or TV show.
- **country** The country or countries where the movie or TV show was produced.
- **release_year** The year when the movie or TV show was released.
- **rating** This columns contains the total previous mails from the same source
- **duration** The rating assigned to the movie or TV show.
- **listed_in** The category or genre under which the movie or TV show is listed
- **description** A brief summary or description of the movie or TV show.

## Dependencies

The project is developed using Python and relies on the following libraries:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Documentation

The project involves the following steps: <br>
<ol>
  <li>  Data Cleaning and Preparation </li>
  <li>  Exploratory Data Analysis </li>
  <li>  Visualization and Insights </li>
  <li>  Hypothesis Testing </li>
  <li>  Feature Enginerring & Data Pre-processing </li>
  <li>  ML Model Training , Implementation and Evaluation </li>
</ol>

### Data Cleaning and Preparation
The first step in this project involves cleaning and preparing the data. This includes checking for missing data, removing duplicates, and converting data types. Some of the specific tasks involved in this step include:

- Handling missing data
- Removing duplicates
- Converting data types
- TimeSeries Analysis

### Exploratory Data Analysis
The next step in the project is to conduct exploratory data analysis.
This involves examining the data to understand its distribution, central tendencies, and correlations between variables.

### Hypothesis Testing

Hypothesis testing , a statistical method used to make inferences about a population based on a sample of data. To perform hypothesis testing on the 'NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv' dataset, we first  start with a null hypothesis (H0) and an alternative hypothesis (H1), then use statistical tests to determine if there is enough evidence to reject the null hypothesis in favor of the alternative hypothesis.

Below is  general step-by-step guide on to perform hypothesis testing on a dataset like NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv:<br>
   <ol>
    <li>  Define the Hypotheses </li>
    <li>  Choose a Significance Level (α)</li>
    <li>  Select the Test </li>
    <li>  Perform the Test</li>
    <li>  Analyze the Results </li>
    <li>  Draw Conclusions </li> 
   </ol>


### Feature Enginerring & Data Pre-processing
<ol>
  <li>Handling Missing Values </li>
<li> Handling Outliers </li>
<li> Label Encoding </li>
<li> Textual Data Preprocessing </li>
<li> Feature Manipulation & Selection </li>
  <li> Data Transformation </li>
<li> Data Scaling </li>
<li> Dimesionality Reduction </li>
<li> Data Splitting </li>
</ol>

### ML Model Training and Evaluation

Following are the ML algorithms on which the model is trained
<ol> 
<li> K-Means </li>
<li> AgglomerativeClustering  </li>
  <li> DBSCAN </li>
</ol>
