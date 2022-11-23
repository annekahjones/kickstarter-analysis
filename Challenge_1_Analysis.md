# Kickstarting with Excel

## Overview of Project
This project helps us dive deeper into the Kickstarter data set. We want to help Louise see how other campaigns performed in relation to their launch dates and their goals. We are able to break apart the data set into smaller, more manageable pieces to get a more precise look at how different aspects of the data compared with others.

### Purpose
The purpose of our analysis was to see if we can find any interesting trends in the data based on the launch date of the campaign and the funding goals of the campaign. We want to see if breaking apart the data in these ways will give us a better idea of whether or not the launch date and goal funds had any impact on the outcome of the campaigns.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
The first deliverable focuses on analyzing the outcomes of the theater parent category based on launch date. We created a pivot table filtered by the parent category and the year the campaign started, rows including the date the campaign was created, columns including three outcomes: successful, failed, and canceled, and the value inside of the pivot table were the counts of the outcomes. We then created a line chart showing the outcomes.

I am not sure if I did the proper thing for adding a screenshot, but I will also add the screenshots to the GitHub.
/Users/annekahjones/Desktop/Screen Shot 2022-11-23 at 8.27.14 AM.png

### Analysis of Outcomes Based on Goals
The second deliverable focuses on analyzing the outcomes of the plays subcategory based on the goals of the campaign. We created a table in a new worksheet with our goals on the rows and our outcomes and percentages on the columns. We found the counts for each otucome and then found the percentage of each outcome out of the total count of projects for each goal. A line chart was then created of the percentages on the y-axis and the goals on the x-axis.

I am not sure if I did the proper thing for adding a screenshot, but I will also add the screenshots to the GitHub.
/Users/annekahjones/Desktop/Screen Shot 2022-11-23 at 8.31.47 AM.png

### Challenges and Difficulties Encountered
I did not encounter any difficulties in deliverable 1. One difficulty that I could see people encountering is not knowing how to reduce the rows down to only the information that you need in the pivot table. When you first add the date created conversion, it has three categories that it creates. You just have to remember to remove the unnecessary categories to get the properly displaying pivot table.

I did encounter some difficulties with deliverable 2. I found the countifs function to be a little confusing. The video explanation definitely helped a lot with understanding the concept more thoroughly. With a little bit of trial and error with our own respective data set, I was able to create the proper functions for each column.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The first conclusion that I can make is that the highest number of successful theater campaigns occurred around May. This may be due to people wanting to go out and do more things as summer is approaching. The second conlusion that I can make is that the number of canceled campaigns remained pretty consistent regardless of the month. I think that looking through the canceled campaigns and the other factors might give us a better idea of what these campaigns had in common to have a consistent amount be canceled regardless of what month it was.

- What can you conclude about the Outcomes based on Goals?
From the line chart that I created, I can see that the percentage of successful and failed campaigns flip-flopped throughout the different goals categories. As the goals were fairly small, the percentage of successful was greater. Then for the mid range of goals, it switched to the percentage of failed being greater. Then it switched again from goals of 35,000 to 45,000. Then the percentage of failed significantly increasead. To me, this shows that the goals were not that telling of a successful campaign or not, because there was so much flipping of the majority percentage holder. 

- What are some limitations of this dataset?
A limitation of this dataset is that the date ranges for the created and ended conversions are only about 8 years: 2009 being the earliest created and 2017 being the latest ended. I think that if we had a longer range of time, we might be able to learn more about the different campaigns. This time period might have economically affected the data since the first created campaign was shortly after the recession of 2008 began. I also see that there are quite a few outliers in the dataset from when we were doing the descriptive statistics portion of this module, so I think removing those from the dataset might give us a different analysis.

- What are some other possible tables and/or graphs that we could create?
I think another table that might be helpful is looking at the outcomes based on the average donation. I wonder if the amount of money that was contributed to the campaign had an association with how it performed. I also think that creating a pie chart of the outcomes for each country might give us a good look at how different campaigns did in each country. It would give a qiuck and easy look at the differences in each countried performance. 
