 Case Study 1: How Does a Bike-Share Navigate Speedy Success?

DATASETS   https://divvy-tripdata.s3.amazonaws.com/index.html

Introduction :

Welcome to the Cyclistic Bike-Share Analysis Case Study! This case study explores how casual riders and annual members use Cyclistic bikes differently and provides insights to help the marketing team design strategies to convert casual riders into annual members.
Project Overview

Objective :

The primary objective of this case study is to analyze the differences in usage patterns between casual riders and annual members of Cyclistic. The goal is to provide actionable insights that will aid in designing marketing campaigns to increase the number of annual memberships.

Data Sources :

The data for this case study consists of historical trip data for Cyclistic bike-share users over the past 12 months. Each month's data is stored in a separate CSV file, which includes details such as start and end times, trip duration, user type (casual or member), and more.

Data Analysis Process : 

The analysis follows the six steps of the data analysis process defined by Google: Ask, Prepare, Process, Analyze, Share, and Act.

1. ASK
   
First phase of the data analysis process, the Ask phase where we have to understand what is the problem stakeholder are trying to solve. 
Here, The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. As a Junior Data Analyst my business task is to understand the behavior of Casual bike riders and Members, also provide insights that going to help the marketing team to launch a campaign to convert casual bike rider to member.

One question that guided my project : 
    How can we convert casuals to members?

2. PREPARE

Then Prepare, preparing data means to collect or use data relevent to the problem we are trying to solve. In this case we have to download twelve csv files, one file represent one month of trip data during the year 2023.
Initially I imported the 12 csv files into individual dataframes then I merge them into a single dataframe.

3. PROCESS

The third phase is to process the data. Data processing is to find various inaccuracies, errors, inconsistencies in the data and get rid of them so that our business problem is not affected.

During this phase, 
I removed any row or column with Not Available Value (NA Value)

I removed duplicated rows

I removed the columns that are of no use

I proofread the spellings

Created columns for my analysis (start hour of trip, month of trip, and finally trip duration)

I removed the trip duration with negative value


4. ANALYZE

In the analyze phase I used various statistics and graph plots to compare the various factors influencing the performance.

Proportion of Trip Duration Analysis :Casual rider's trips are 1.89 times longer than member's trips

Seasonal Trends: Ride counts increase during favorable weather (spring and summer). During summer, casual riders and members have almost equal ride counts.

Bike Type Usage: Members primarily use classic bikes, while casual riders favor docked and electric bikes.

Percentage Casual riders and Members

Preferred Routes

Rush hour visualization

5. SHARE
   
After a long time of coding, looking for some help on Stack Overflow and analysis it's time to share my insights and to answer to the question "How can we convert casuals to members?"

The best way to do it is to create a slideshow with contrast, artistic principles (size, color, shape), one chart by slide, and oral explanation. 
Another way is to create a Dashboard with Power BI or Tableau for example.

6. ACT
   
The sixth phase of data analysis is to use every insight we learn from phase four. We have to provide to stakeholders any information that going to help them make a decision. 

Considering the observations in phase 4 I can suggest :

     Introduce a summer pass to attract casual riders during peak riding season.
     
     Create a weekend pass targeting casual riders who use bikes for leisure activities.
     
     Promote the health benefits and environmental advantages of biking to encourage more commuters to become annual members.
