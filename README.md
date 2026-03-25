Netflix Exploratory Data Analysis (EDA) 🎬
Project Overview
This project is part of the Synent Technologies Internship Program (Task 3). The goal is to perform a comprehensive Exploratory Data Analysis (EDA) on the Netflix dataset to uncover trends, patterns, and insights regarding movies and TV shows available on the platform.

Dataset Description
The dataset consists of listing of all the movies and tv shows available on Netflix, including details like:

Type: (Movie or TV Show)

Director & Cast

Country of production

Release Year & Rating

Listed In: (Genres)

 Tech Stack & Libraries
Python 

Pandas: For data cleaning and manipulation.

Matplotlib & Seaborn: For data visualization.

Google Colab: Environment used for development.

 Data Preprocessing
To ensure accuracy, the following steps were taken:

Handling Missing Values: Filled missing values in director, cast, and country with "Unknown".

Imputation: Filled missing rating values using the mode (most frequent value).

Data Cleaning: Verified data types and removed any inconsistencies.

 Key Insights
Based on the visualizations, here are the main findings:

Content Distribution: Movies significantly outnumber TV Shows on the platform.

Production Growth: There is a massive surge in content production after 2010, peaking around 2018-2019.

Top Creators: The United States and India are the leading contributors to Netflix's library.

Popular Genres: International Movies, Dramas, and Documentaries are the most frequent categories.

Repository Structure
netflix_titles.csv: The raw dataset.

synent-task3-netflixeda.ipynb: The Jupyter Notebook containing the code and analysis.

README.md: Project documentation.

 Author
Arwa Ghandour
Software Development Student & Data Science Intern at Synent Technologies.

 Demo Video
Click here to watch the project walkthrough https://drive.google.com/file/d/1rCrZvzrjNTCQE9_PSMz1IyyjeytkLcz6/view?usp=sharing
