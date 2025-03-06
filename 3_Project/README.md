# Introduction 
#### I started this project to practice and brush up on skills in Python and relevant libraries required for Data Analysis while also learning some new skills. I have noticed that the ability to  leverage Python is important and companies everyday are requiring their data analysts to learn how to utilize this powerful tool. So I created this repository to showcase my core Python Skills for employers. For my first project, I recreated a project that was done by Luke Barousse who is a Youtuber that posts valuable info and tutorials on data analytics. I have linked the video I used for this project along with Luke's Github below! 

### Libraries Used:
- Matplotlib
- Pandas
- Seaborn 
- Numpy


#### Video Link:  https://www.youtube.com/watch?v=wUSDVGivd-8&t=20753s 

#### Github Link: https://github.com/lukebarousse

# Required Job Skills
## Analysis 
#### Finding the most popular skills in job postings required some basic filtering of the dataframe followed by exploding the job skills list into individual rows. After adjusting the dataframe to what I needed I plotted the data into bar charts with each bar representing a different skill. 
#### View the notebook with detailed steps [[here](3_Skills_Demand.ipynb)]:


![Visualization of skills percentages](images/skill_demand_percentages.png)

## Insights
#### In the image above you'll see the percentage chance that a skill will be required for a specific job. The plot shows that Python is a sought after skill and is typically one that Data Scientists and Data Engineers need to know. Data Analysts also need to know Python as well but it is not as common. Additionally SQL is typically a required skill in over 50% of job postings for Data Analysts and Data Scientists. 

# Trends of Job Skills 
## Analysis 
#### It is important to know what job skills are required for certain roles, but what if certain skills are not as useful as time goes on? I wanted to observe the trend of job skils for data analyst roles. To do this I filtered my data for Data Analyst roles in the United States. After doing this I created a pivot table showing counts of job skills by the month. After getting my final dataframe, I filtered my data for the top 5 most prevalent skills and created a line chart using the seaborn library.

#### View the notebook with detailed steps [here](4_Skills_Trends.ipynb)
![job skills trend viz](images/skills_trend.png)

## Insights 
#### As you can see from the image, there is no skill that seems to be increasing or decreasing in prevelancy rapidly. We notice a slight decrease in the likelihood that SQL will be in a job posting but even with the decrease, SQL still remains the most common skill required for Data Analysts. Adittionally Python had a short burst in August where it trended above Tableau but it quickly went back to normal the following month.

# Salary Analysis 
## Analysis
#### Similar to previous notebooks, in this notebook I wanted to do some more analysis on Data Analyst jobs in the United States. I created two seperate dataframes with the Top 10 most common skills for data analysts and the Top 10 skills with the highest median salaries.
#### View the notebook with detailed steps [here](5_Salary_Analysis.ipynb)

![salary viz](images/salary_viz.png)

## Insights
#### Its important to note that the skills that match with the highest median salaries are not exactly the most accurate. Diving deeper into the data we notice that the number of job postings with the highest median salaries are quite low. The sample size of the data is too small to make any conclusions about the data. What we notice from the lower subplot is that knowing Python, Tableau and R will be beneficial in getting a higher salary whereas Microsoft tools like Powerpoing, Excel and Word are typically not as valuable to learn.
