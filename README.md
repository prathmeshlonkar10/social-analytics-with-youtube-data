# 📊 Optimizing YouTube Posting Strategy: A Simple Data-Driven Analysis

## 🔍 Overview
This data science project analyzes global YouTube trending videos to uncover patterns and insights about what makes videos trend on the platform. The analysis explores various aspects, including video categories, channel characteristics, publishing patterns, engagement metrics, and regional trends. Additionally, the project implements machine learning models to predict video view counts, providing content creators with valuable insights for optimizing their videos. The project culminates in an A/B testing framework that can optimize posting strategies.

## 📁 Dataset
There are several ways to collect YouTube data, including the official "YouTube Data API v3". However, to get things moving fast, this notebook uses the [Kaggle YouTube Trending Videos dataset](https://www.kaggle.com/datasets/canerkonuk/youtube-trending-videos-global). This dataset is updated daily on Kaggle and includes:  

- Video metadata (ID, title, description, tags, duration, etc.)
- Channel information (title, subscriber count, country, age, etc.)
- Engagement metrics (views, likes, comments)
- Trending information (trending date, trending country)

**Dataset size**: 3,389,193 records x 28 columns (roughly 6.5GB)

## 🧪 Components
1. Data Cleaning & Preprocessing
   - Redundant columns
   - Missing values
   - Datetime conversions
2. Feature Engineering
   - 13 new columns engineered
5. Exploratory Data Analysis (EDA)
   - Trends & patterns
   - Data visualization
7. Predictive Modeling
   - Random Forest
   - Feature importance
9. A/B Testing
   - Weekday vs Weekend 
   - Morning vs Evening
   - Engagement performance 

## 📈 Key Visualiations

![Screenshot 2025-06-07 172757](https://github.com/user-attachments/assets/89c4b4be-3d3c-4ea2-93d6-8973fa3c6609)
![Screenshot 2025-06-07 172810](https://github.com/user-attachments/assets/2fb2ff76-cac7-4a3f-ba12-d978d8a0046e)
![Screenshot 2025-06-07 172825](https://github.com/user-attachments/assets/49705360-7e2b-4c00-ab39-109a5c67bf93)
![Screenshot 2025-06-07 172835](https://github.com/user-attachments/assets/9b231e1f-fb5d-40ed-a267-5678627bdc89)
![Screenshot 2025-06-08 144033](https://github.com/user-attachments/assets/de698111-e4ee-4925-b6be-619075d905b4)
![Screenshot 2025-06-08 181618](https://github.com/user-attachments/assets/7b9eb9c7-28d9-468e-b423-0aed9c8f26ea)
![Screenshot 2025-06-08 181629](https://github.com/user-attachments/assets/4d407f8f-b31d-4eaf-98f4-72145c970889)

## 🧠 Key Findings
- Evening posts may get less reach on average.
- Though fewer views, evening viewers are more engaged (more likes).
- More people are watching on weekends, likely due to free time.
- Weekday audience is more interactive in terms of likes & comments.

## ✅ Few Recommendations for Creators
- Post videos in the evening (5–9 PM) if your goal is engagement quality (likes/comments per view).
- Morning may be better if reach (total views) is the primary goal.
- Target weekdays (Mon–Fri) for high-engagement posts.

## 🚀 Potential Use Cases
- Optimize Posting Time: Use A/B testing results to schedule posts for maximum engagement (e.g., post in the morning for higher views and likes).
- Competitor Benchmarking: Track performance of competitor channels and replicate successful content strategies.
- Ad Strategy Alignment: Use category popularity trends and engagement metrics to guide ad placement or influencer partnerships.
