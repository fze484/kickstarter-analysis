# Kickstarting with Excel

## Overview of Project
We want to know how different campaigns fared in relation to their launch dates and their funding goals. Using a Kickstarter dataset we will visualize campaign outcomes based on their launch dates and their funding goals. 

### Purpose
The goal is to understand the trends in kickstarter theater projects' success rate in relation to their start date as well as their funding goal.   

## Analysis and Challenges
### Analysis
The kickstarter database contains the financial goals and amounts pledged by category and subcategory for different kickstarter ideas in different fields, including theater, technology, music etc. Each parent catergory is subdivided into sub-category. For example, theater kickstarters can be divided into plays, musicals and spaces. For the purpose of this analysis, we will focus on the theater category and the plays sub-category. The database also contains an outcomes column, which describes the failed, successful, canceled fund-raising projects. This database also contains the launch date of each play, as well as other metrics not used for this anlysis, but which can also be used to draw a different set of conclusions. 
We created a pivot table containing the outcome of kickstarter plays (failed, successful or canceled plays) based on their launch date and another pivot table describing the seasonality of successful, failed and canceled plays. 
Based on this analysis, we are able to determine, the optimal amount of money that should be raised (the goal) based on historical data of 1066 kickstarter plays from 2011 to 2017, and the right time period to launch the fund-raising process in the theater industry based on 1393 kickstarter theater ideas from 2010 to 2017. 
### Challenges


### Analysis of Outcomes Based on Launch Date
Looking at Theater_Outcomes_vs_Launch.png, we can infer that the most successful kickstarter theater projects, in absolute terms, were launched during the months of May and June. 
However, the number of kickstarters launched during those 2 months alone contributed an average of 24% of the total kickstarters launched throughout the other months of the year. This means that theater creators were more inclined to start a fund-raising campaign during summer time.
To better decide on which month a campaign should be launched, we should convert these numbers into ratios and look at the success rate, rather than the number of successful theater campaigns. 
In doing so see Percentage_Successful_Theater_Campaigns.png, we can conclude that the month with the highest success rate is the month of May. 80% of theater campaigns succeeding in meeting their financial goals. We ca, also conclude that the lowest success rate occured when kickstarters were launched in December, where only 65% of campaigns succeeded in meeting their goals. 

### Analysis of Outcomes Based on Goals
According to Outcomes_vs_Goals.png, the most successful campaigns for plays are ones that asked for less than $4999, where the success rate is above 70% as well as those with a goal ranging from $35,000 to $44,900, with a success rate of 67%. The success rate drops substantially as the goal increases as soon as the goal goes from less than $4999 to over $5000, going from over 70% success rate to 55% success rate when the goal is between $5000 to $9999. Because campaigns with larger funding requests (between $35K and $44,999) received a high success, this shows that goal isn't the only predicator for campaign success. These campaigns were either exceptionally well-run (good marketing, etc.) or the quality of the plays pitched was exceptionally good (talented directors, actors, good storyline etc.)

### Challenges and Difficulties Encountered

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
The most successful campaigns occur during the most of May. 
The least succssful ones occur during the month of December.

- What can you conclude about the Outcomes based on Goals?
The lower the goal, the higher the likelihood of success. However, success rate may be dependent on other implied variables such as marketing, quality and the people involved in the plays. 

- What are some limitations of this dataset?
The theater dataset has some gaps in terms of number of datapoints per year. For example, 2010 only contains 1 data point for the month of July, while 2015 and 2016 contains data for all the months of the year. This may be a limitation as data may not be consistent throughout the years. 

The excercise doesn't focus on one particular market, we are using global data. The dynamics in one country may differ from country to country. It would have been best to focus on one country for the analysis. 

Although plays represent 77% of total theater kicstarters, which means that plays significantly affect the theater category as a whole, it would have been best to focus on the sub-category "plays" for the outcomes based on launch date analysis. 

- What are some other possible tables and/or graphs that we could create?
Because the financial goal isnùt the only predictor of campaign success, it is crucial to understand other variables that may influence success. The duration of the campaign may be a good variable to analyze. A chart containing the length of the campaign vs success rate could help better guide our understanding of campaign success. 
This analysis would be more accurate if one were to look at a specific geography (US, GB, etc.) Thus, re-doing these pivot tables with each country would help guide our understanding of how successful theater/plays campaigns are, depending on the popularity of this industry in different markets. 
Another useful variable would be the average donation per backer while looking at different goals at the same time. This metric could help us understand how much each person should donate, on average, to meet a certain goal. This could be important in order to understand the reach that each campaign should aim for. 