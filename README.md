# Movie-Sentiment-Analysis

# ETL Pipeline for Tweet’s Sentiment Analysis

**Project Duration:** September 2022 - December 2022

## Overview

This project focuses on creating an automated ETL (Extract, Transform, Load) pipeline for sentiment analysis of tweets, particularly those related to Netflix. The pipeline involves data extraction, preprocessing, and sentiment analysis to gain insights into public sentiment regarding Netflix.

## Key Features

- Automated data pipeline using Airflow to extract 500 Netflix tweets daily for 7 days and store them in Amazon S3.
- Algorithm deployment using the NLTK library for preprocessing, refining, and contextualizing text data.
- Sentiment analysis accuracy assessment using three different Naïve Bayes distribution models (GaussianNB, MultinomialNB, BernoulliNB) with an impressive 80.8% accuracy achieved using the Multinomial Naïve Bayes model from the sklearn library.

## Prerequisites

Before running the pipeline, ensure you have the following dependencies installed:

- [Python](https://www.python.org/downloads/)
- [Airflow](https://airflow.apache.org/docs/apache-airflow/stable/start.html) for pipeline orchestration
- [NLTK](https://www.nltk.org/) for natural language processing
- [scikit-learn](https://scikit-learn.org/stable/install.html) for machine learning tasks

