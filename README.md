# Website Performance Analysis

Exploratory Data Analysis (EDA) of hourly website traffic data (April 6 – May 3, 2024), examining user behavior, session engagement, and traffic patterns across different marketing channels using Python.

## 📊 Project Overview

This project analyzes ~3,182 hourly records of website performance data to uncover:
- Which traffic channels drive the most visitors
- Which channels bring the highest-quality (most engaged) traffic
- How traffic and engagement change throughout the day
- Where the biggest opportunities for improvement lie

## 🛠️ Tools & Libraries

- **Python**
- **Pandas** – data cleaning and transformation
- **NumPy** – numerical operations
- **Matplotlib** & **Seaborn** – data visualization

## 🔍 Key Steps

1. **Data Loading & Cleaning** – Fixed misaligned headers, converted date/hour columns to datetime, converted numeric columns from object to proper numeric types, checked for null values.
2. **Feature Engineering** – Extracted `Hour` from the datetime column for time-based analysis.
3. **Exploratory Analysis & Visualization**:
   - Users & Sessions trend over time
   - Total users by channel
   - Average engagement time by channel
   - Engagement rate distribution by channel
   - Engaged vs. Non-Engaged sessions by channel
   - Traffic heatmap by hour and channel
   - Engagement rate vs. sessions over time

## 📈 Key Insights

- **Organic Social** drives the most traffic (~47.5K users) but has inconsistent engagement quality.
- **Referral** traffic has the smallest volume but the best, most consistent engagement rate.
- **Direct** traffic has the weakest engagement more non-engaged sessions than engaged ones.
- Traffic follows a clear daily cycle: lowest between **12 AM–5 AM**, peaking between **6 PM–10 PM**.
- **Email** and **Organic Video** channels are almost unused, representing untapped opportunity.
- A major traffic spike occurred around **April 17–18**, worth further investigation.

## ✅ Recommendations

- Improve landing pages and CTAs to boost Direct traffic engagement.
- Invest more in Referral partnerships best quality-to-volume ratio.
- Better match Organic Social content to landing pages to reduce drop-off.
- Schedule content/ads during peak hours (6 PM–10 PM).
- Test and grow underused channels like Email and Organic Video.
- Track engagement rate (not just traffic volume) as the core success metric.
