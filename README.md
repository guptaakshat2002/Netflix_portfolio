Netflix Titles Exploratory Data Analysis (EDA)



📌 Project Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on the Netflix Titles dataset. The dataset contains information about various movies and TV shows available on Netflix, including their genre, country of origin, release year, rating, and more.

📄 Dataset

The dataset used in this project is netflix_titles.csv. It contains:

Title

Director

Cast

Country

Date Added

Release Year

Rating

Duration

Genre (Listed In)

🎯 Objectives

Data Cleaning and Preprocessing

Feature Engineering

Visualizing Distribution of Movies vs TV Shows

Identifying Most Common Genres

Analyzing Content Added Over Time

Classifying Content into Age Groups

🛠️ Libraries Used

pandas

seaborn

matplotlib

🔄 Data Preprocessing

1. Missing Value Treatment

Filled missing rating with the mode.

Filled missing country with "Unknown".

Dropped rows with missing cast and director.

2. Date Transformation

Converted date_added to datetime format.

Extracted year_added from date_added.

3. Genre Extraction

Extracted the primary genre from the listed_in column.

4. Age Group Classification

Classified content into Kids, Teen, Adult, and General based on rating.

📊 Visualizations

Distribution of Movies vs TV Shows

Top 10 Most Common Genres

Content Added Over the Years

🔍 Insights

The majority of content on Netflix consists of Movies compared to TV Shows.

Documentaries and Dramas are the most common genres.

Netflix significantly increased its content library between 2016-2020.

Most content is targeted towards Adult and Teen audiences.

🚀 How to Run

Install the required libraries:

pip install pandas seaborn matplotlib

Place the netflix_titles.csv file in the project directory.

Run the notebook or script to generate visualizations and insights.

🎯 Conclusion

This project provides a comprehensive analysis of the Netflix catalog, uncovering key trends in content distribution, genre popularity, and audience targeting.

📌 Future Improvements

Sentiment Analysis on movie descriptions

Recommendation System

Time Series Analysis for predicting future content additions

📧 Contact

For any inquiries or contributions, feel free to reach out at your-email@example.com.

Give this project a ⭐ if you like it!
