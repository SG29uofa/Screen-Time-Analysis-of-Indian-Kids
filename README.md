# Screen-Time-Analysis-of-Indian-Kids
Data analysis and hypothesis testing project using Python, Pandas, and visualization to compare screen time by gender.

This is an early-stage data science project focused on statistical analysis and insights where I explored how much screen time kids in India are getting every day. I used basic tools like charts and statistics (EDA and hypothesis testing) to look for patterns and find out if there’s any difference in screen time between boys and girls.

Problem Statement
In this project, I explored a simple but important question:
Do boys and girls spend different amounts of time on screens each day?
Understanding screen time is important because it can affect children’s health, behavior, and daily routines. 

To answer this question, I used a dataset of Indian kids and applied basic data analysis and a t-test (a type of statistical test) to compare the average screen time between boys and girls.

Dataset
Indian Kids Screen Time Dataset on Kaggle (https://www.kaggle.com/datasets/ankushpanday2/indian-kids-screentime-2025)

Objectives
•	Analyze the distribution of screen time among children
•	Compare screen time patterns between boys and girls
•	Perform a statistical test to check if the difference is significant

Steps Performed
•	Loaded and explored the dataset
•	Visualized screen time distribution using histograms and boxplots
•	Calculated average screen time for each gender
•	Conducted a two-sample t-test (independent) to compare means
•	Interpreted the result with plain English explanation

Statistical Test
Null Hypothesis (H₀): Boys and girls have the same average screen time  
Alternative Hypothesis (Ha): Boys and girls have different average screen time

Why did we use a t-test?
  We used a t-test because:
•	The sample size is relatively small
•	The population standard deviation is unknown
•	We are comparing the means of two independent groups (boys vs girls)

Result
•	The test returned a p-value greater than 0.05  
•	We failed to reject the null hypothesis, meaning there is no statistically significant difference between average screen time of boys and girls in this dataset.

Tools Used
•	Python
•	Pandas
•	Seaborn & Matplotlib
•	SciPy
•	Jupyter Notebook

