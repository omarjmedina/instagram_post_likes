# Instagram Likes Analysis

## Project Overview
This project analyzed Instagram likes across different content categories to uncover engagement trends. On this repository there is an uploaded **Jupyter Notebook file** (`omedina_instagram_post_likes.ipynb`) with all the analysis. 

Using Python (`pandas`, `seaborn`, `matplotlib`), we simulated, cleaned, visualized, and statistically analyzed the data to gain insights into content performance.

## Process & Challenges

### Data Generation & Cleaning
- Created a dataset with **500 Instagram posts**, each assigned a category and a random number of likes.
- Handled missing and duplicate values using `.dropna()` and `.drop_duplicates()`.
- Converted `Date` to `datetime` format and ensured `Likes` were integers, ensuring accuracy.

### Data Visualization
- 📊 **Histogram of Likes** revealed the overall engagement distribution across posts.
- 📌 **Boxplot of Likes per Category** highlighted which content types received more likes.
- Choosing the best visualization was a challenge, but testing different graphs helped identify the most informative ones.

### Statistical Analysis & Insights
- The **average number of likes per post** was **~5000**.
- **Food, Fashion, and Fitness** categories received the highest engagement, indicating users prefer these content types.
- **Travel and Culture** posts had lower engagement, suggesting they might require better captions, hashtags, or posting times to improve reach.

## What Sets This Project Apart?
✅ **Realistic Instagram Analytics Simulation**: The dataset structure mirrors real social media insights, making the analysis practical for businesses.  
✅ **Actionable Insights for Social Media Strategy**: Helps brands & influencers decide which content types to focus on.  
✅ **End-to-End Data Pipeline**: Covers data generation, cleaning, visualization, and analysis in a single project.  

## Future Improvements & Business Applications
📊 **Time-Based Analysis**: Study engagement trends based on posting time & day of the week.  
🤖 **Machine Learning for Prediction**: Predict which posts will go viral based on category and past likes.  
📈 **Deeper Instagram Metrics**: Extend analysis to comments, shares, and follower growth for richer insights.  
