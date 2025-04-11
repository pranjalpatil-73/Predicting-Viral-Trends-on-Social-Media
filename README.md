# Predicting Viral Trends on Social Media

## Project Overview
This project is about finding out what kind of YouTube videos are likely to go viral, before they actually do. We use machine learning and data from trending videos to give businesses early insights into rising trends, so they can take action ahead of others.

## Problem Statement
Many businesses miss big opportunities because:
- They notice trends too late.
- They don't have good tools to spot trends early.
- They waste money on trends that are already fading.

We solve this by predicting which topics or styles will go viral in the next 30 to 90 days using YouTube data.

## Dataset
We use the “Trending YouTube Video Statistics” dataset from Kaggle. It contains:
- Video titles
- Tags and hashtags
- Views, likes, dislikes, and comments
- Publish times
- Dates when videos started trending

[Dataset Link](https://www.kaggle.com/datasnaek/youtube-new)

## Methodology
### 1. Data Cleaning
- Removed duplicates and missing values
- Cleaned up video tags
- Converted date columns to proper format

### 2. Exploratory Data Analysis (EDA)
- Looked at trends in views, likes, and comments
- Found patterns in how and when videos trend

### 3. Feature Engineering
- Created a metric for engagement rate: (likes + comments) / views
- Extracted and analyzed hashtags
- Added features like how many days since upload

### 4. Modeling
- Used a Random Forest Classifier to predict viral videos
- Used Prophet to forecast engagement growth
- Used K-Means to group similar content types

### 5. Recommendations
- Found the top content clusters with high engagement for early investment

## Business Impact
1. **Spot trends early** so brands can jump in before competitors
2. **Stay ahead** of the market by focusing on new viral topics
3. **Spend marketing money smarter** by avoiding trends that are already old
4. **Get better returns** by acting early on popular content

## Business Insights
### 1. Engagement Rate Matters
Videos with more likes and comments per view are more likely to go viral.

### 2. Timing is Critical
Videos that trend within 7 days of being uploaded are more likely to go viral.

### 3. Best Trend Clusters
- **Cluster 3**: Tech Reviews (Engagement Rate: 0.12)
- **Cluster 7**: Fashion Hauls (Engagement Rate: 0.10)
- **Cluster 5**: Fitness Tutorials (Engagement Rate: 0.09)

### 4. Hashtags Help
Trending hashtags like #TechTuesday or #OOTD boost visibility.

## Business Metrics
1. **Engagement Rate** = (Likes + Comments) / Views
2. **Viral Prediction Accuracy** = 85% using the Random Forest model
3. **Trending Time** = Days between upload and trending
4. **Cluster Engagement Rates**:
   - Tech Reviews: 0.12
   - Fashion Hauls: 0.10
   - Fitness Tutorials: 0.09

## Results
- 85% accuracy in predicting viral videos
- Forecasted a 15% increase in engagement over 90 days
- Identified the top video clusters for early business investment

## Future Work
1. Add data from other platforms like Instagram, TikTok, and Twitter
2. Use advanced NLP models like BERT or GPT for better text analysis
3. Build a system that detects trends in real time
4. Improve model performance with hyperparameter tuning

## How to Use This Project
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/predicting-viral-trends.git
   ```
2. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```
3. **Run the Jupyter Notebook**:
   - Open `Predicting_Viral_Trends.ipynb`
   - Run all the cells to see the analysis and results

4. **Explore outputs**:
   - Visualizations and model files are in the `results/` folder
   - Cleaned dataset is in `processed_data.csv`

## Contact
- Email: your-email@example.com
- LinkedIn: Your LinkedIn Profile
- GitHub: Your GitHub Profile




   
