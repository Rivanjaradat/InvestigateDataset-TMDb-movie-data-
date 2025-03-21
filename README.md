## Project Overview

### Introduction
This project involves the analysis of a dataset obtained from The Movie Database (TMDb), which contains detailed information about over 10,000 movies. The primary objective of this project was to explore and analyze the dataset to answer various questions regarding the financial and popular performance of movies. Additionally, the project aimed to identify potential relationships between factors such as genre, release date, budget, and revenue.

### Project Implementation

1. **Data Cleaning:**
   - The dataset was loaded and opened using the `pandas` library in Python.
   - Duplicate records were identified and removed to ensure the accuracy of the analysis.
   - Missing values in certain columns were handled appropriately.
   - Columns were converted to the appropriate data types, including converting the `release_date` column to a datetime format using `pd.to_datetime`.

2. **Exploratory Data Analysis (EDA):**
   - Descriptive statistics were generated for key columns, such as budget and revenue, to summarize the dataset.
   - Various visualization techniques were employed to explore the relationships between variables, including the correlation between movie popularity and release year.
   - Plots were created to investigate the impact of genre on revenue generation.

3. **Answering Analytical Questions:**
   - **Question 1**: Do different genres of movies generate higher revenues?
     - The analysis revealed that genres such as "Action" and "Adventure" tend to generate significantly higher revenues compared to other genres.
   
   - **Question 2**: How does movie popularity correlate with the release year?
     - A correlation was found between movie popularity and release year, with more popular movies generally being released in recent years.
   
   - **Question 3**: Is there a relationship between movie budget and revenue?
     - The analysis indicated that higher-budget movies tend to generate higher revenues; however, there were notable exceptions where movies with lower budgets achieved considerable earnings.

4. **Conclusions:**
   - Certain genres, such as "Action" and "Adventure," are more likely to generate higher revenues.
   - Movies released in recent years generally experience higher popularity.
   - There is a general trend where higher-budget movies tend to achieve higher revenues, though there are exceptions.

---

### Technologies Used:
- **Python**: The primary programming language utilized for data analysis.
- **pandas**: A library used for data manipulation and cleaning.
- **matplotlib** and **seaborn**: Libraries used for data visualization.
- **Jupyter Notebook**: The development environment employed for interactive code execution.


