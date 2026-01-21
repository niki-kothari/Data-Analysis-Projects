# LendingClub
This is lending club project
🧾 Lending Club Loan Default Analysis Project
📘 Overview

This project is based on analyzing data from a Lending Club Loan dataset. The goal of the project was to understand how different customer and loan-related factors affect whether a person will default on their loan.
I worked to clean the data, analyze customer behavior, and visualize patterns that can help the club make better lending decisions.

🎯 Objective

 The main objective of this project was to:

> Understand and explore the loan dataset.

> Clean the data by removing duplicates, null values, and unnecessary columns.

> Analyze trends and relationships between loan amount, term, interest rate, and other features.

> Visualize the findings through various types of plots.

> Provide recommendations based on insights from the analysis.

🛠️ Technologies Used

> Python

> Pandas

> NumPy

> Matplotlib

> Seaborn

> Jupyter Notebook

🧩 Dataset

The dataset contains information about loans issued by a lending company.
It includes features like:

> Loan amount

> Term

> Interest rate

> Annual income

> Loan status

> Purpose

> Grade

> Payment history, etc.

The dataset helps us understand which types of customers are more likely to default on their loans.

🧹 Data Cleaning

I started by checking for:

> Null values

> Duplicate rows

> Unnecessary or unrelated columns

After detecting issues, I dropped the unused columns and filled or removed missing values. This helped in preparing a clean dataset that could be used for better analysis and visualization.

📊 Data Analysis & Visualization

I used different visualization libraries like Matplotlib and Seaborn to explore the relationships between features.
Some of the plots included:

> Loan amount vs Interest rate

> Loan purpose distribution

> Count of loan status (fully paid vs charged off)

> Income level and default rate

These visualizations helped me find key insights such as which customer segments were riskier and how loan amount or term affected repayment.

⚠️ Mistakes and Challenges

While working on this project, I faced some challenges:

At first, I didn’t handle missing and duplicate data properly, which gave wrong analysis results.

Some graphs were unclear because of uncleaned categorical data.

I tried to analyze too many columns at once, which made it hard to focus on meaningful results.

💡 Solutions & Improvements

To fix these mistakes, I:

Rechecked data cleaning steps carefully using isnull() and duplicated() functions.

Focused only on important features that affect loan defaults.

Added proper labels, titles, and legends to all graphs.

Wrote short explanations below each chart to make the notebook more readable.


📈 Conclusion

Through this project, I learned how important data cleaning and visualization are in any real-world data analysis.
I gained practical experience in handling messy datasets, using Python libraries effectively, and communicating results clearly.
This project gave me confidence in working with financial data and taught me how to make insights that are useful for decision-making.
