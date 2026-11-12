# Data-visualization-with-Tableau

# Student Habits and Academic Performance:

Interactive Tableau dashboards that explore how daily habits (study time, sleep, exercise, diet, and screen time) relate to students' exam scores and mental health. Course project for Data Visualization with Tableau.

## Dataset
- **Name:** Student Habits and Performance Dataset
- **Source:** [Kaggle: Student Habits vs Academic Performance](https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance)
- **Size:** 1,000 students, 16 fields (one row per student)
- **Key fields:**
  - Study Hours/Day
  - Sleep Hours
  - Exercise Frequency (per week)
  - Mental Health Rating (1-10)
  - Exam Score

## Tools and Techniques
- **Tool:** Tableau Desktop
- **Charts:** scatter plots, bar charts, tree maps
- **Features:** tooltips, annotations, trend lines, filters, interactive dashboards

## Dashboards
- **Dashboard 1:** Relationships between study hours, sleep hours, exercise, mental health, and exam scores.
- **Dashboard 2:** Netflix hours, diet quality, sleep hours, and exam scores.

## Key Insights
- **Study time:** Students who study about 3-5 hours per day tend to score higher and more consistently. Extra study beyond that shows diminishing returns.
- **Sleep:** More sleep is linked to better mental health ratings, and has a weaker positive link with exam scores.
- **Exercise and diet:** More frequent exercise and healthier diets are linked to small but steady gains in average scores.
- **Screen time:** Heavy Netflix and social media users are concentrated in the lower score range.
- **Part-time jobs:** Students with jobs study slightly fewer hours and score marginally lower, but the gap is small.

## Challenges and Solutions
- Too many charts made the views confusing, so I simplified each dashboard to one main chart per question.
- Some variables were highly correlated, so I used averages instead of sums and wrote clear titles and tooltips.

## Future Work
- Apply the dashboards to a larger, real-world dataset across courses and semesters.
- Add simple predictive models (regression or basic machine learning) and more variables, such as stress and course difficulty.

## Screenshots
![Dashboard 1](images/dashboard1.png)
![Dashboard 2](images/dashboard2.png)

## Live Dashboard
[View on Tableau Public](add-your-link-here)

## Files
- `Final_Report.pdf`: full project report
- `student-habits.twbx`: Tableau workbook
- `images/`: dashboard screenshots

## Author
Sandeep Kaur

*Note: The patterns shown are correlations in this dataset, not proof of cause and effect.*
