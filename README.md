
# Analysis Documentation

## **1. Project Overview**
This project explores the FIFA 21 dataset to analyze player attributes, ratings, and market values. The goal is to preprocess and clean the data, perform exploratory data analysis (EDA), and uncover insights into player performance and value distribution.

## **2. Dataset Description**
The dataset contains information about FIFA 21 players, including:
- **Name**: Player's name
- **Club**: Team they play for
- **Value & Wage**: Market value and salary
- **Overall & Potential Rating**: Player's current and expected performance level
- **Physical Attributes**: Height, weight, preferred foot, etc.
- **Skill Metrics**: Passing, shooting, dribbling, defending, etc.

## **3. Data Cleaning & Preprocessing**
To ensure data quality, the following preprocessing steps were performed:
- Dropped unnecessary columns
- Fixed newline issues in the 'Club' column
- Converted 'Value', 'Wage', and 'Release Clause' to numerical values
- Transformed 'Height' and 'Weight' into numeric formats
- Handled missing values in key attributes
- Processed categorical data for further analysis

## **4. Exploratory Data Analysis (EDA)**
EDA was conducted to identify trends in the dataset. Key analyses include:
- **Top 10 Rated Players**: Identifying the highest-rated players
- **Lowest 10 Rated Players**: Analyzing the least-rated players
- **Distribution of Player Overall Ratings**: Understanding rating trends across all players

## **5. Visualizations**
The following were created to illustrate trends and insights:
- **Histogram of Player Ratings**: Shows how overall ratings are distributed
- **Barchart of Nationality**
    - Top 10 Nationalities Represented in FIFA 21
    - Top Rated Players and their Club
- **Wage vs. Overall Rating**: Scatter plot analyzing player salaries and performance

## **6. Conclusions & Findings**
- The majority of players have an overall rating between 60-80.
- A strong correlation exists between player wage and overall rating.
- High-value players tend to belong to top-tier clubs.
- Data preprocessing significantly improved the dataset's usability.

This project demonstrates essential data wrangling, visualization, and analysis skills, providing meaningful insights into FIFA 21 player attributes.
```

