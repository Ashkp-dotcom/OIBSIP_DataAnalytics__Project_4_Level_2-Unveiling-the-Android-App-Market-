# Unveiling the Android App Market

## 📌 Project Objective
The objective of this project was to analyze the **Google Play Store dataset** to uncover trends, patterns, and user behaviors in the Android app market. The focus was on cleaning the dataset, handling missing values, converting datatypes, and performing exploratory data analysis (EDA).

## 🔧 Steps Performed
1. Fixed incorrect datatypes:
   - Converted `Price` to numeric by removing symbols (`$`, `,`) and casting to integer.
   - Converted `Last Updated` column to `datetime` and extracted **Year** and **Month**.
2. Removed irrelevant columns such as `Current Version` and `Android Version`.
3. Handled missing values using median imputation.
4. Performed exploratory data analysis (EDA) using **barplots, countplots, and distributions**.

## 📊 Insights from Analysis

### 🗂 App Data (Google Play Store)
- **App Size by Category**:  
  Games (39 MB) are the heaviest, followed by Family (26 MB) and Sports (22 MB). Parenting and Travel apps are also relatively large.
- **App Count by Category**:  
  Family (1832) and Games (959) dominate, followed by Tools (827) and Business (420).
- **Average User Ratings by Category**:  
  Events (4.39), Education (4.36), and Art & Design (4.35) are the highest-rated.
- **Installs by Category**:  
  Games (13.8B), Communication (11B), and Tools (8B) lead installs. Productivity (5.8B) and Social (5.4B) also show strong reach.
- **Rating by App Type**:  
  Paid apps (4.27) are rated slightly higher than Free apps (4.18).
- **Apps Published Over Time**:  
  Explosive growth post-2015, peaking in 2018 with 6284 apps published.

### 💬 User Review Data
- **Sentiment Distribution**:  
  Positive (64%), Negative (22%), Neutral (14%) — majority are positive.
- **Sentiment Polarity**:  
  Positive (+0.37), Neutral (0), Negative (-0.26) → indicates polarization between satisfied and frustrated users.
- **Sentiment Subjectivity**:  
  Reviews are largely subjective: Positive (0.56), Negative (0.53), Neutral (0.08).

## 🚀 Key Takeaways
- Games & Family apps dominate in volume and installs, but **Education** and **Events** apps lead in ratings.  
- Paid apps show **slightly higher satisfaction** than free apps.  
- The Android app market **boomed post-2015**, peaking in 2018.  
- Reviews are **mostly positive**, but 22% negative reviews highlight improvement areas in app performance and experience.  
- Review content is largely **opinion-driven**, so qualitative insights matter alongside ratings.

## 🛠 Tools & Libraries
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Jupyter Notebook

## 📌 Conclusion
This project highlighted how data cleaning and EDA can uncover meaningful insights about the Android ecosystem. The findings reveal growth patterns, category dominance, user satisfaction trends, and sentiment distributions that can help developers and businesses make data-driven decisions in the app market.

## 👤 Author
Ashish Kumar Paswan  
Oasis Infobyte Internship (Data Science Domain)
