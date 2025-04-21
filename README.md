# 📸 InstaBot 2

InstaBot 2 is a powerful Instagram scraping and analysis tool. It allows you to scrape recent posts from public Instagram handles, extract hashtags, calculate their frequencies, and visualize engagement metrics such as likes and hashtag popularity.

---

## 🚀 Features

- Scrapes public Instagram profiles.
- Extracts captions, hashtags, and like counts from recent posts.
- Calculates frequency of hashtags and stores them in a CSV file.
- Identifies the top 5 most popular hashtags.
- Calculates the average number of likes for each handle.
- Visualizes data with:
  - 📊 A pie chart of top hashtags.
  - 📉 A bar chart showing average likes per handle.

---

## 📂 Output Files

- `hashtags_frequency.csv`  
  | Hashtag | Frequency |  
  |---------|-----------|  
  Stores each hashtag and how many times it was used.

- `top_hashtags_pie_chart.png`  
  A pie chart showing the top 5 most frequently used hashtags.

- `average_likes_bar_chart.png`  
  A bar chart showing the average number of likes per Instagram handle.

---

## 🛠️ Installation

Make sure you have Python installed. Then, install the required libraries:

```bash
pip install requests beautifulsoup4 pandas matplotlib
