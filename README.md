# kickstarter-analysis
## An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends then using visualizations in order to display the data in a more ogranized and coherent fashion. Primary focus was serving our client in that she was in the process of starting up a crowdfunding project (theatre/plays) with a budget of $4000. After sorting through a large amount of kickstarter data, I was able to seperate what was valuable to her and what wasn't based on the Parent Category of theatre and Subcategory of plays from all over the country. Using data tables, pivot tables, pivot charts and different variations of visualizations it was much easier for us to gain a clear undertsanding of the reality of success that she may be able to achieve in her crowdfunding project.


# Kickstarting with Excel

## Overview of Project
The purpose of this project is to perform data analysis on thousands of crowdfunding campaigns on kickstarter to reveal any trends that will help us serve out client who is in the market for a crowdfunding project.
### Purpose
The purpose of the analysis and revealing any trends is to help our client get a better understanding of the rate of success and failure these crowdunding campaigns based on a multidude of factors such as Launch Date, Funding Goal, Amount Pledged, etc.
## Analysis and Challenges
I performed my analysis using a combination tools such as filtering through main data set then producing pivot tables and pivot charts in order to further anaylze trends among filtered and unfiltered data. The main problem for me was completing Deliverable 2 aka Outcomes Based on Goals analysis. This delieverable is the reason that I am submitting this late, it was alot of trouble for me due to the fact that whenever I tried to use the function in order to get a count of outcomes based on a number range, I kept getting errors. Finally after watching many youtube videos and reading over the module, I believe that I succesfully completed what was asked of me. 
### Analysis of Outcomes Based on Launch Date

- What are two conclusions you can draw about the Outcomes based on Launch Date?

First conclusion I can draw about outcomes based on launch date would be that April - June is a time frame where crowdfunding theatre/play would be the most succesful with the peak being in the month of June. Second conclusions would be that the worst time for a crowdfunding theatre/play would be around October because thats when the most campaigns fail according to the data.

![](images/Theater_Outcomes_vs_Launch.png) 

### Analysis of Outcomes Based on Goals

- What can you conclude about the Outcomes based on Goals?

The main conclusion that can be made based on the "Outcomes based of Goals" data would be that most campaigns with lower goals have the tendency to succeed where as the campaigns with larger goals have a lower tendency to succeed. While there are some excpetions to this statment, for the most part as the goals increase, success decreases and as goals decrease, success increases showing a negative correlation.

![](images/Outcomes_vs_goals.png) 
### Challenges and Difficulties Encountered

The main challenge and difficult was Deliverable 2 , for some reason whenever I tried to poluate the line chart using the data I had, it simply was not working. After watching the video in the module over and over and using some GOOGLE-FU. I realized I had to manually input the "$" for =COUNTIFS(KickstarterDataCopy!$D:$D,"<1000" which I believe solved my problem.

## Results

- What are some limitations of this dataset?

Some limitations of this data set is that I believe it could have included more valuable categories such as length of the play, or genre of the play which would have further helped analyze specifically the type of plays that succeed rather than just based on monetary values.


- What are some other possible tables and/or graphs that we could create?

We could have created another table that just conatined number of succesful based on location of plays but instead of creating a line chart or column chart, a Pie graph could have been used to display the total number of succesful,failed, and canceled based on location of plays which could have gave a clear representation of the success rates based on location. This would have helped our client clearly and quickly see the most succesful, failed, and cncled based on geographic location.
