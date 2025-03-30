# Text Data Analysis: YouTube Case Study
## Overview

This project explores YouTube video trends using data analysis techniques. It involves analyzing audience engagement, sentiment analysis, word cloud generation, emoji usage, and video popularity trends. The dataset is collected, cleaned, and stored in multiple formats (CSV, JSON, and SQLite database).
## Technologies Used
* Python: Main programming language for analysis. 
 
* Pandas: For data manipulation and analysis.
 
* Matplotlib & Seaborn: For data visualization.
  
* WordCloud: For generating word clouds.
 
* TextBlob: For sentiment analysis.
 
* Emoji Library: For analyzing emojis in text.
 
* SQLite: For exporting data into a database.
 
* JSON/CSV: For data export formats.
## Project Structure
📂 youtube-analysis  
│-- 📜 youtube_analysis.ipynb  # Jupyter Notebook with full analysis  
│-- 📂 data  
│   │-- US_category_id.json  # Category data  
│   │-- youtube_data.csv  # Main dataset  
│-- 📂 exports  
│   │-- cleaned_data.csv  # Processed data  
│   │-- analysis_results.json  # Analysis summary  
│-- 📂 images  
│   │-- wordcloud.png  # Word cloud image  
│   │-- sentiment_chart.png  # Sentiment analysis visualization  
│-- 📜 README.md  # Project documentation  
## Data Collection & Processing

The dataset consists of YouTube video metadata, including titles, categories, views, likes, dislikes, and comments. The data was collected and processed using Pandas, and stored in multiple formats such as CSV, JSON, and SQLite database for further analysis.

### Steps Involved in Data Processing:

Data Loading – Imported YouTube dataset from CSV and JSON files.

Data Cleaning – Removed missing values and standardized text formats.

Data Exporting – Stored cleaned data in CSV, JSON, and a SQLite database.
## 📈 Data Analysis & Insights  

### 🔥 1. Trending Video Categories  
- Identified the **most liked** and **most viewed** video categories.  
- Analyzed **likes-to-category** distribution to determine which categories receive the highest audience engagement.  

### 📊 2. Sentiment Analysis on Comments  
- Used **TextBlob** to classify audience sentiment into **Positive, Neutral, and Negative** categories.  
- Generated separate **word clouds** for **positive and negative comments**, highlighting key words associated with different sentiments.  

### ☁️ 3. Word Cloud Analysis  
- Created a **word cloud** to visualize frequently used words in **video titles & comments**.  
- Generated **two separate word clouds**:  
  - **Positive Word Cloud** – Shows words from comments classified as **positive**.  
  - **Negative Word Cloud** – Shows words from comments classified as **negative**.  

### 😊 4. Emoji Analysis  
- Detected and analyzed **emojis** in YouTube comments.  
- Identified the **top 10 most frequently used emojis**, representing audience emotions.  
- The most commonly used emojis were: **😂🔥👍❤️ (list 6 more emojis from analysis)**.  

### 📉 5. Likes-to-Category Chart  
- Created a **chart comparing likes** across different **video categories**.  
- Identified which **categories** receive the most audience **approval and engagement**.  

### 🔄 6. Views & Likes Relationship  
- Analyzed the **correlation between views and likes** to understand how engagement impacts video popularity.  
- Visualized the **trend between highly viewed videos and their like count**.  

### 📊 7. Views, Likes & Dislikes Correlation  
- Explored the relationship between **views, likes, and dislikes** to identify patterns.  
- Found whether a higher number of **views always translates to more likes** or if there are cases where **dislikes are significantly higher**.  
