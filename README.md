# 📊 **Netflix Titles Data Analysis**

## 🎬 **Project Overview**
This project explores the **Netflix Titles Dataset**, performing **Exploratory Data Analysis (EDA)** to uncover insights about Netflix's content library, trends, and patterns. 📺🔍

---

## 📌 **Key Insights**

### 1️⃣ **Content Distribution**
✅ Movies make up **~70%** of Netflix's content, while TV Shows account for **~30%**.  
✅ Dramas and Comedies are the most prevalent genres. 🎭😂

### 2️⃣ **Release Year Trends**
📈 Most content was released post **2010**, showing Netflix's **rapid expansion** in content production.  
📉 **Older content (before 2000)** is scarce, suggesting a focus on modern productions.  

### 3️⃣ **Geographical Insights** 🌍
🌟 The **United States, India, and the UK** dominate Netflix's catalog.  
❗ Many records are missing country information, affecting precise geographical analysis.

### 4️⃣ **Duration Trends** ⏳
🎥 **Movies** typically range from **80 to 120 minutes**.  
📺 **TV Shows** often have **1-3 seasons**.  

### 5️⃣ **Missing Data Issues** ❗
🧐 Fields like **Director, Cast, and Country** contain significant missing values.  
🔄 Data cleaning is needed for robust insights.

---

## 🔧 **Next Steps & Further Analysis**

### ✨ **Data Cleaning & Preprocessing**
🔹 Impute missing values or filter out incomplete records.  
🔹 Standardize categorical values (e.g., normalize country names).  

### 🔥 **Advanced Analytics**
📊 **Trend Analysis**: Identify changing content preferences over the years.  
🤖 **Machine Learning**: Predict content success based on genre, duration, and country.  
📝 **Sentiment Analysis**: Analyze descriptions for audience sentiment insights.  
🎯 **Recommendation System**: Develop a Netflix-style content recommender.  

---

## 🚀 **Get Started**

### 📥 **Installation**
```r
# Load necessary libraries
install.packages(c("tidyverse", "dplyr", "ggplot2", "skimr", "DataExplorer"))
library(tidyverse)
library(dplyr)
library(ggplot2)
library(skimr)
library(DataExplorer)
```

### 📂 **Run EDA**
```r
# Load dataset
netflix_data <- read.csv("netflix_titles.csv")

# Quick overview
skim(netflix_data)

# Generate automated EDA report
create_report(netflix_data)
```

---

## 💡 **Contributions & Feedback**
💬 Feel free to **fork**, **modify**, and **contribute** to this project!  
📧 Reach out for suggestions or collaborations. 🚀

---

✨ *Netflix, Chill, and Analyze!* 🍿📊
