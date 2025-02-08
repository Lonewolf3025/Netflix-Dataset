# 🎬 Netflix Titles EDA 📊  

> *"It's not just a streaming service; it's a data goldmine!"* 🚀  

![Netflix Banner](https://media.giphy.com/media/3ohs4BSacFKI7A717y/giphy.gif)  

---

## 🔍 **Exploring Netflix's Content Universe**  
This project dives deep into the **Netflix Titles Dataset**, uncovering trends, patterns, and insights about the ever-growing streaming giant.  

---

## 📌 **Key Insights**  

✔️ **Movie Dominance**: 🎥 70%+ of Netflix content is movies, while TV shows make up the rest.  
✔️ **Boom in Content**: 📈 Steady increase in new releases over the years, peaking in recent times.  
✔️ **Top Producing Countries**: 🌍 USA, India, UK lead in content creation.  
✔️ **Missing Data Challenge**: 🚨 Many entries lack director, cast, or country details.  
✔️ **Most Popular Genres**: 🎭 Drama & Documentaries dominate, followed by Comedy.  

---

## 📊 **Exploratory Data Analysis (EDA)**  

### 🎭 **Top 5 Genres on Netflix**  


🎥 **Drama** is the most common genre, making up a significant portion of Netflix’s content library.  

### 📅 **Content Production Over the Years**  
```python
import matplotlib.pyplot as plt  
df['release_year'].value_counts().sort_index().plot(kind="bar", color="red", figsize=(12,6))  
plt.title("Netflix Content Production Over Years", fontsize=14)  
plt.xlabel("Year")  
plt.ylabel("Number of Titles")  
plt.show()


🚀 Next Steps
🔹 Advanced Analytics: Content recommendation models 📡
🔹 Sentiment Analysis: Audience reactions based on descriptions 📢
🔹 Genre Clustering: ML-based content categorization 🤖
🔹 Time-Series Forecasting: Predicting content growth trends ⏳

👨‍💻 Tech Stack
💻 Language: Python 🐍
📦 Libraries: pandas, matplotlib, seaborn, tidyverse, funModeling, dplyr

📜 Contributing
🚀 Want to improve this analysis?
Fork this repo, make changes, and submit a PR!

📧 For queries, reach out via LinkedIn or email.

Email: bharathyadav3052@gmail.com
Linkedin: www.linkedin.com/in/b-bharath-7017b124b
