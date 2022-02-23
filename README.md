# kickstarter-analysis
Performing Analysis on Kickstarter data to uncover trends. This data has been collected from the past crowdfunding projects from 2009 to 2017, in various categories as theatre,food,music etc.</br>
By Analyzing this data we will gain insights as to how the various campaigns fared in relation to their funding goals, launch dates etc.  

## Table of Contents
- [Overview of Project](#OverviewProject)
  * [Purpose](#purpose)
  * [Background](#Background)
- [Analysis and Challenges](#AnalysisandChallenges)
  * [Analysis based on Category](#AnalysisCategory)
  * [Analysis based on Sub-Category](#AnalysisSubcategory)
  * [Analysis based on Launch Date](#Analysislaunchdate)
  * [Analysis of Outcomes Based on Goals](#AnalysisGoals)
  * [Statistical Analysis of "Plays" subcategory in US](#StatisticalAnalysis)
- [Challenges and Difficulties Encountered](#Challenges)
- [Results](#results)
- [Limitations of the dataset](#Limitations)
- [Summary](#summary)
- [References](#references)


## <a name="OverviewProject"></a>Overview of Project

Louise is an upcoming playwright, who wants to start a crowdfunding campaign to help fund her play "Fever". She is estimating a budget of $10,000. 
Hence we need to analyze the crowdfunding data to see if there are any specific factors that make the project campaign sucessful. we will help Louise to 
set up her own campaign and set her up for success. Using excel to analyze the current site data will help her gain a greater understanding of campaigns from
start to finish and will be able to set her campaign to mirror other successful ones in the same category. we will help Louise kickstart her production.

## <a name="AnalysisandChallenges"></a>Analysis and Challenges

1. Before starting the analysis, we gazed through the data given. We organized and sorted the data by segregating the category and sub-category from the 
'Category and Subcategory' column. We filtered our data on "theatre" category and "Plays" subcategory.
2. We changed the "Launched Date" and the "deadline" columns from the "Unix time stamp" format 'to a standard date format. 
3. We did this so as to analyze the duration of the campaigns and understand if the success of the camapign is dependent on when it was launched.
4. With the help of bar charts we analyzed in which were the campaigns most successful. This will help louise understand the best time to launch her play. 
5. In order to understand how the campaigns were funded, we calculated the average donation by the number of backers. Also, we analyzed with the help of charts the goal amount of each campaign and the total amount it was able to fund.
6. Louise was inspired by five plays she saw at the Edinburgh Festival Fringe and wanted to know how they were funded. Hence we analyzed these plays from Great Britain and 
   inferred that the mean goal amount for these plays was $2100.
7. Finally, we deepened our analysis for Louise by adding statistical components.
   

### <a name="AnalysisCategory"></a>Analysis based on Category
From the figure below we see that in US the most successful campaigns belong to the "Theatre" category. 57% of Theatre campaigns were 
successful in "US". "Music" being the second most successful campaign.

<p align="center"> <img src = "Resources\Data Report.png" width ="45%"> </p> 

### <a name="AnalysisSubCategory"></a>Analysis based on Sub-Category
In US the most successful sub-category in theater is "Plays", as shown in the figure below. we infer that 61% of the plays were successful in US.
 
<p align="center"> <img src = "Resources\Subcategory_analysis.png" width ="45%" align="center"> </p>

### <a name="AnalysisLaunchDate"></a>Analysis based on Launch Date
From the figure below we infer that the most successful "Theatre" campaigns were launched in the month of May and it tapers 
off by the end of the year. A total of 319 campaigns were launched in the month of May and June. Out of which 211 campaigns were successful, 
with a success rate of 66%. 
The winter season, that is the months of november and december,may be the worst time to launch the campaign with a success rate of only 55%.  

<p align="center"> <img src = "Resources\Theater_Outcomes_vs_Launch.png" width ="45%" align="center"> </p>
 
 ### <a name="AnalysisGoals"></a> Analysis of Outcomes Based on Goals
 We did an analysis on the number of campaigns that were successful based on their goal amount. As shown in the figure below, the most successful 
 campaigns had a goal less than 5,000. About of 73% campaigns were successful with a goal amount ranging from $1000 to $4999. The higher the amount goal, 
 the less campaigns were successful. 
 Since Louise has campaign goal of about $10,000, it seems that it would be difficult to get the number of backers to successfully fund her play.
 
<p align="center"> <img src = "Resources\Outcomes_vs_Goals.png" width ="45%" align="center"> </p>

### <a name="StatisticalAnalysis"></a>Statistical Analysis of "Plays" subcategory in US
We did a statistical analysis by filtering data for "Plays" subcategory in US. From the below snapshot we determine that the failed kickstarter campaingns have much higher 
fund raising goals (mean=$10,554) than the successful kickstarter campaigns(mean = $5,049).
We also see that mean and median pledged amounts of failed campaigns are much lower than the succesful campaingns. Hence, we infer that there might be other reasons for the 
Kickstarter cmpaigns to fail, other than large funding.

<p align="center"> <img src = "Resources\Statistical Analysis.png" width ="45%" align="center"> </p>

## <a name="Challenges"></a>Challenges and Difficulties Encountered

## <a name="Results"></a>Results
1. In US the most successful campaigns belong to the "Theatre" category and "plays" sub-category. This seems like a good news for Louise.
2. May or June might be the best time to launch her play "Fever". Winter months being the worst.
3. The most successful campaigns in US had a goal ranging from $1000 to $4999. Since Louise has a funding goal of $10,000 , she might face some difficulties to get the 
   backers for her play.

## <a name="Limitations"></a>Limitations of this dataset

1. From the statistcal analysis we inferred that the mean and median pledged amounts of failed campaigns are much lower than the succesful campaigns. Hence large goal amount was not the only reason for the failure of the campaigns. There were other factors too that contributed to the failure of the campaigns. But with this dataset, we are unable to identify those other factors. Hence a more detailed data would be required.
2. Loise would also like to know the other factors that make a play successful. Such as, the targeted audience who would love to come and watch plays. She may also like to know the best way to advertise her campaign which would make it successful. Such information is missing from the dataset to give Louise a detailed report.
3. The data ranges from the year 2009 to 2018 only. Louise would be more interested in the latest data from the previous years. 
 
- What are some other possible tables and/or graphs that we could create?

## <a name="summary"></a>Summary

## <a name="references"></a> References
[1] [Stock Analysis Excel File]( )
[2]
