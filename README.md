# LeetCode Data Analysis

## 📌 Introduction
This project focuses on exploratory data analysis (EDA) of a dataset comprising questions from LeetCode, one of the most popular coding platforms for programmers. Using Python, Pandas, and visualization libraries such as Seaborn, we aim to uncover insights into question patterns, difficulty levels, acceptance rates, and more, to assist developers in better understanding and navigating the platform.

## 📊 Dataset Overview
The dataset includes the following columns:

- **Question_No**: Unique identifier for each LeetCode question.
- **Question**: Title of the question.
- **Topic_tags**: Tags indicating the conceptual topics of the question. (Values such as "1+", "2+", etc., imply multiple topics.)
- **Acceptance**: Acceptance rate for each question (percentage).
- **isPremium**: Indicates whether the question requires a premium subscription (True or False).
- **Difficulty**: Difficulty level (Easy, Medium, Hard).
- **Question_Link**: URL link to the question on LeetCode.
- **Solution**: URL link to the solutions provided for each question.

## 🎯 Objectives
- Perform EDA to identify key patterns in LeetCode questions.
- Analyze the relationship between question difficulty and acceptance rate.
- Examine the distribution of questions by difficulty and premium status.
- Explore topic tags to understand popular concepts covered on LeetCode.

## 🔍 Insights Gained
- **Difficulty Analysis**: Distribution of questions across difficulty levels (Easy, Medium, Hard).
- **Acceptance Rate Trends**: How acceptance rates vary with difficulty and premium status.
- **Topic Tag Analysis**: Identification of frequently appearing tags, indicating common concepts on LeetCode.
- **Premium vs Free Questions**: Comparison between premium and non-premium questions in terms of difficulty and acceptance rates.

## 📈 Visualization Highlights
- **Bar Plots**: Show distribution of question difficulties.
- **Box Plots**: Explore the acceptance rate by difficulty level.
- **Word Clouds**: Represent most common topic tags visually.
- **Histograms**: Analyze the acceptance rate distribution among different question types.

## 🚀 Tech Stack
- **Python**: Core programming language.
- **Pandas**: Data manipulation and analysis.
- **Seaborn/Matplotlib**: Data visualization.

## 📥 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/kumawatmanish05/leetcode-data-analysis.git
