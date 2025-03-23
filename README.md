# Predicting-Viral-Trends-on-Social-Media
This project predicts viral trends using YouTube data, enabling businesses to capitalize on emerging trends early. Key insights: high engagement rates and timely content drive virality. Metrics: 85% prediction accuracy, top clusters (tech, fashion) with 10-12% engagement rates. #DataScience #TrendForecasting

# Predicting Viral Trends on Social Media: A Data-Driven Approach to Early Trend Detection Using YouTube Data

## Project Overview
This project aims to **predict viral trends on social media platforms** by analyzing YouTube video data. Using machine learning and data analysis techniques, we identify early-stage trends and provide actionable insights for businesses to capitalize on these trends before they go mainstream. The project focuses on **engagement metrics**, **hashtags**, and **time-based features** to forecast viral content.

---

## Problem Statement
Businesses often miss early-stage trends, leading to lost market opportunities. This project addresses the following challenges:
- **Late Trend Detection**: Companies react to trends after they’ve already gone viral.
- **Missed Opportunities**: Brands fail to capitalize on emerging trends due to lack of predictive insights.
- **Inefficient Marketing**: Marketing budgets are spent on trends that have already peaked.

Our solution leverages **YouTube data** to predict which topics, products, or styles will go viral in the next **30-90 days**, enabling businesses to invest early and gain a competitive edge.

---

## Dataset
The dataset used in this project is the **Trending YouTube Video Statistics** dataset from Kaggle. It includes metadata about trending YouTube videos, such as:
- **Video Title**
- **Tags**
- **Engagement Metrics** (views, likes, dislikes, comments)
- **Publish Time**
- **Trending Date**

**Dataset Link**: [Trending YouTube Video Statistics](https://www.kaggle.com/datasnaek/youtube-new)

---

## Methodology
The project follows a structured data science workflow:

### 1. Data Cleaning
- Handled missing values and duplicates.
- Cleaned the `tags` column and extracted hashtags.
- Converted `publish_time` and `trending_date` to datetime format.

### 2. Exploratory Data Analysis (EDA)
- Analyzed distributions of views, likes, dislikes, and comments.
- Visualized trending videos over time.
- Identified correlations between engagement metrics.

### 3. Feature Engineering
- Created **engagement_rate** as a key feature.
- Extracted **hashtags** and performed text analysis using TF-IDF.
- Added time-based features like **days_since_upload**.

### 4. Modeling
- Trained a **Random Forest Classifier** to predict viral videos.
- Used **Prophet** for time-series forecasting of engagement rates.
- Applied **K-Means Clustering** to group similar trends.

### 5. Recommendations
- Identified top clusters with high engagement rates for early investment.

---

## Business Impact
This project provides significant value to businesses in the following ways:
1. **Early Trend Detection**: Enables brands to identify and invest in trends before they go viral.
2. **Competitive Advantage**: Helps businesses stay ahead of competitors by capitalizing on emerging trends.
3. **Optimized Marketing Spend**: Allows marketers to allocate budgets more effectively by focusing on high-potential trends.
4. **Increased ROI**: Early investment in viral trends can lead to higher returns on marketing campaigns.

---

## Business Insights
### 1. **Engagement Rate is a Key Indicator**
- Videos with higher engagement rates (likes + comments per view) are more likely to go viral.
- Brands should focus on creating content that encourages viewer interaction.

### 2. **Time Matters**
- Videos that trend within **7 days of upload** have a higher chance of going viral.
- Brands should prioritize timely content creation and promotion.

### 3. **Top Clusters for Investment**
- Clusters with high engagement rates represent the most promising trends.
- For example, **Cluster 3** (tech reviews) and **Cluster 7** (fashion hauls) showed the highest engagement.

### 4. **Hashtags Drive Visibility**
- Videos with trending hashtags (e.g., #TechTuesday, #OOTD) are more likely to trend.
- Brands should incorporate relevant hashtags into their content strategy.

---

## Business Metrics
The following metrics were used to evaluate the success of the project:
1. **Engagement Rate**: (Likes + Comments) / Views
2. **Viral Prediction Accuracy**: Accuracy of the Random Forest Classifier in predicting viral videos.
3. **Trending Time**: Number of days between video upload and trending date.
4. **Cluster Engagement**: Average engagement rate for each cluster.

---

## Results
- The **Random Forest Classifier** achieved an accuracy of **85%** in predicting viral videos.
- The **Prophet model** forecasted a **15% increase in engagement rates** over the next 90 days.
- Top clusters for early investment:
  - **Cluster 3**: Tech Reviews (Engagement Rate: 0.12)
  - **Cluster 7**: Fashion Hauls (Engagement Rate: 0.10)
  - **Cluster 5**: Fitness Tutorials (Engagement Rate: 0.09)

---

## Future Work
1. **Incorporate Additional Data Sources**: Integrate data from platforms like Instagram, Twitter, and TikTok for a more comprehensive analysis.
2. **Advanced NLP Techniques**: Use BERT or GPT for better hashtag and topic analysis.
3. **Real-Time Trend Detection**: Build a real-time system to monitor and predict trends as they emerge.
4. **Hyperparameter Tuning**: Optimize model hyperparameters for better performance.

---

## How to Use This Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/predicting-viral-trends.git

   **Install Dependencies:**
   pip install -r requirements.txt

Run the Jupyter Notebook:

Open Predicting_Viral_Trends.ipynb in Jupyter Notebook.

Execute the cells to reproduce the analysis and results.

Explore the Results:

Check the results/ folder for visualizations and saved models.

Review the processed_data.csv file for the cleaned and processed dataset


Contact
For questions or collaborations, feel free to reach out:

Email: your-email@example.com

LinkedIn: Your LinkedIn Profile

GitHub: Your GitHub Profile
   
