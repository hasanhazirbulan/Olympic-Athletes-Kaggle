# 🏅 120 Years of Olympic History: Athletes and Results - EDA

This project explores **120 years of Olympic history** through **Exploratory Data Analysis (EDA)** using data from the Olympic Games between **1896 and 2016**. The goal is to uncover trends, patterns, and interesting insights related to athletes, countries, sports, and medal achievements.

---

## 📂 Dataset Overview

The dataset contains records of over 270,000 athletes who participated in the Olympic Games. Each row represents an athlete’s participation in a specific event.

📄 **Key columns include**:
- `Name`: Athlete’s name  
- `Sex`: Gender of the athlete (`M` or `F`)  
- `Age`, `Height`, `Weight`: Physical information (may have missing values)  
- `Team`: Country/region represented  
- `NOC`: National Olympic Committee code  
- `Games`, `Year`, `Season`, `City`: Time and location of the Olympic Games  
- `Sport`, `Event`: Sport and specific event  
- `Medal`: Type of medal won (`Gold`, `Silver`, `Bronze`, or NaN)

---

## 🎯 Project Objectives

- Clean and preprocess the dataset (handle missing values, duplicates)
- Analyze athlete demographics (age, height, weight) over time and by sport
- Explore gender participation trends from 1896 to 2016
- Identify top-performing countries and most successful sports
- Visualize medal distributions across years, countries, and events

---

## 📊 Key Questions Explored

- How has **gender participation** evolved over the last century?
- Which countries have won the **most medals** overall and in specific sports?
- What is the **average age, height, and weight** of athletes in different sports?
- Are there any patterns in **medal winners' demographics**?
- Which **sports and events** have been the most consistently featured?

---

## 📌 Key Insights

- Male participation dominated early Olympics, but **female representation has increased steadily**, especially after the 1980s.
- The **USA, USSR, Germany, and China** are among the top-performing countries across all time.
- Some sports like **gymnastics and diving** tend to have younger athletes, while others like **equestrian** have older participants.
- There are noticeable changes in **athlete body metrics** (height, weight) over time in various sports.

---

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** – for data manipulation
- **NumPy** – for numerical operations
- **Matplotlib** & **Seaborn** – for data visualization
- **Jupyter Notebook** – for interactive analysis

---

## 📁 How to Run

1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/heesoo37/120-years-of-olympic-history-athletes-and-results)
2. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/olympics-eda.git
