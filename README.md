# 📊 YouTube Trending India Analysis

A data analysis project using the India-specific YouTube Trending dataset. This project explores what type of content goes viral in India by analyzing trending video data — including views, likes, comments, publish time, and tags.

---

## 📁 Dataset

- **Source**: [YouTube Trending Video Statistics (Kaggle)](https://www.kaggle.com/datasets/rsrishav/youtube-trending-video-dataset)
- **File Used**: `INvideos.csv`

---

## 🔍 Analysis Performed

- 🏆 **Top 10 Trending Channels** by average views  
- 🗓️ **Days to Trend**: Time taken between upload and trending  
- ☁️ **Most Common Tags** using WordCloud  
- 📈 **Top Trending Categories** by frequency  
- 📊 Engagement comparisons across metrics (likes, views, comments)

---

## 🛠️ Tools & Libraries

- `Python`  
- `Pandas` – Data processing  
- `Matplotlib` & `Seaborn` – Visualizations  
- `WordCloud` – Text-based visual insight  
- `Google Colab` – Notebook environment

---

## ⚙️ Key Fixes Made

- Handled malformed CSV rows using `on_bad_lines='skip'`  
- Solved timezone mismatch (`tz-aware vs tz-naive`) during datetime subtraction  
- Cleaned missing/invalid tag data

---

## 📌 Sample Visuals

- Horizontal bar chart of top channels by average views  
- Histogram of `days_to_trend`  
- WordCloud of most used tags  
- Bar plot of most frequent video categories

---

## 🚀 How to Run

1. Upload `INvideos.csv` to Colab  
2. Run the notebook cells in order  
3. Outputs will include charts and insights  
4. You can export the notebook or results as needed

---

## 📬 Author

- **GitHub**: [@IgoCUCKOO](https://github.com/IgoCUCKOO)

---

## 💡 License

MIT License – free to use, just credit if you fork or reuse 🙌
