# Kickstarting with Excel

## Overview of Project

### Purpose 
The purpose of this challenge was to create a report for Louise that visualizes other theatre/play campaign outcomes based on their funding goals and based on their launch date, so she can compare how her campaign did with other campaigns in the theatre/play category. 

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
I created a chart by extracting the launch date of each campaign and noting the outcome for that particular campaign. The outcomes for each possible result (successful, failed, cancelled) were added together and plotted against the date to see if there was a trend. 

![Theatre_Outcomes_vs_Launch_Date](https://user-images.githubusercontent.com/90593897/134580901-8b6346ad-1031-4421-bd61-b082464a2534.png)

The line chart shows that campaigns with a launch date in May had the highest number of successful campaigns. Louise could take this into consideration and may want to launch campaigns in May as opposed to the end of the year, where there were the least amount of successful campaigns.  

### Analysis of Outcomes Based on Goals

I extracted this data by counting the number of successful, failed, and cancelled theatre/play campaigns within different funding goal brackets by using the COUNTIFS feature in Excel. The percentage of outcomes was then plotted against the different funding goal brackets to find trends.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/90593897/134580950-ab4f4342-36cf-4669-bf20-204393a1501c.png)

The line chart shows that the highest rate of successful campaigns (~80%) occurs when the funding goal is less than $1,000. If a higher goal is desired, the chart suggests that Louise may want to aim for a funding goal of $35,000-$40,000 as this range had the second highest success rate. She should definitely avoid a funding goal of $45,000 or greater, as theatre/play campaigns with this funding goal were not as successful as those with funding goals less than $1,000. 

### Challenges and Difficulties Encountered 
I encountered some difficulty in creating the pivot chart to ultimately create a graph with goals on the independent axis, and percentage outcomes on the y-axis. It took some thinking but ultimately, it made sense. I learned how pivot tables can provide many unique ways to visualize your data. It does take some thinking to know where you should put certain values or variables to ultimately create a chart that is intuitive for readers, like Louise, to understand. 

## Results

**What are two conclusions you can draw about the Outcomes based on Launch Date?**

	1) Per the data we have, the best month to launch a campaign for a play would be May.
	2) The worst month to launch a campaign for a play would be December. 

**What can you conclude about the Outcomes based on Goals?**

	1) Campaigns with funding goals that are less than $1,000 tend to be more successful than those with higher funding goals, such as $45,000 or higher.  

**What are some limitations of this dataset?**

	Our data is limited in that we do not have information on additional factors that may drive results. Such factors include play genres, length of funding time, and information on how popular plays are in different countries. With additional data, we could see if some play genres do better than others, if there is a "sweet spot" for campaign funding length, and which countries may like plays more than other countries. This information would also be useful to Louise to give her the best chance at a successful production. 

**What are some other possible tables and/or graphs that we could create?**
Since we do have data on countries, we could graph this information against campaign outcomes to try and find a relationship between which countries may have more successful play campaigns. We could also add in backer count to see if we find a country that has more play backers. 
