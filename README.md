# 📊 Optimizing YouTube Posting Strategy: A Simple Data-Driven Analysis

## Overview
This data science project analyzes global YouTube trending videos to uncover patterns and insights about what makes videos trend on the platform. The analysis explores various aspects including video categories, channel characteristics, publishing patterns, engagement metrics, and regional trends. Additionally, the project implements machine learning models to predict video view counts providing content creators with valuable insights for optimizing their videos. The project culminates in an A/B testing framework that can optimize posting strategies.

## Dataset
There are several ways to collect YouTube data, including the official "YouTube Data API v3". However, to get things moving fast, this notebook uses the [Kaggle YouTube Trending Videos dataset](https://www.kaggle.com/datasets/canerkonuk/youtube-trending-videos-global). This dataset is updated daily on Kaggle and includes:  

- Video metadata (ID, title, description, tags, duration, etc.)
- Channel information (title, subscriber count, country, age, etc.)
- Engagement metrics (views, likes, comments)
- Trending information (trending date, trending country)

**Dataset size**: 3,389,193 records x 28 columns (roughly 6.5GB)
