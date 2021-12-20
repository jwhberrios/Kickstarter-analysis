# Kickstarter-analysis
Performing kickstarter analysis to look for trends
# An analysis of Kickstarter Campaigns
Analysis of fundraising campaigns from various theatrical productions worldwide
# Kickstarting with Excel
Upcoming playwright, Louise, wants to start a crowdfunding campaign to help fund her play, “Fever”. Her estimated budget is $12,000.
Crowd funding data was analyzed to determine the factors that contributed to previous successful crowdfunding campaigns in the same category as her play, so Louis can utilize those factors to successfully run her own crowdfunding campaign to fund, “Fever”. 
The theater category was found to be the most successful in Great Britain and May was the month with the highest number of successful kickstarter campaigns.
## Overview of Project
### Purpose
Louise came close to meeting her fundraising goal in a short amount of time and with new found confidence and eagerness to further improve in another fundraising campaign to meet her goal, she wants to know how other campaigns did based on their funding goal and launch dates.
The purpose of this analysis was to determine how other crowdfunding campaigns performed based on their funding goal and launch dates. In order to address these two questions: 
- A pivot table and line chart was created to visually represent the outcomes of theaters worldwide based on their launch date as presented in the screenshot here ![Pivot_table_outcomes_based_on_launch_date](C:\Users\16462\Desktop\BootCamp\Module 1_Excel\Module 1 Challenge\Pivot_table_outcomes_based_on_launch_date.png).
- A line chart was created to visually analyze campaign outcomes that were successful, failed, or canceled based on a range of different funding goals as presented in the screenshot here ![Data_outcomes_based_on_funding_goal](C:\Users\16462\Desktop\BootCamp\Module 1_Excel\Module 1 Challenge\Data_outcomes based on funding goal.png).
## Analysis and Challenges
### Analysis of Outcomes Based on Launch Date
![Theater_outcomes_vs_launch](C:\Users\16462\Desktop\BootCamp\Module 1_Excel\Module 1 Challenge\Resources\Theater_outcomes_vs_Launch.png)
### Analysis of Outcomes Based on Goals
![Outcomes_vs_Goals](C:\Users\16462\Desktop\BootCamp\Module 1_Excel\Module 1 Challenge\Resources\Outcomes_vs_Goals.png)
### Challenges and Difficulties Encountered
When inputing the command on excel to run (COUNTIFS) to determine campaign outcomes based on funding goals, I had to be extra metriculous to ensure the code was proper to ensure the correct calculation was performed by the program. Upon multiple attempts after reviewing the video on bootcampspot, I finally inputted the correct code to run an analysis on the cell without any error messages. 
However, I quickly realized the numbers didn't look accurate when I extended the code to other cells to correspond different campaign outcomes with different funding goal ranges. I realized the subcategory was not inputted correctly on my kickstarter spreadsheet; the title was not appropriately labeled either ![Incorrect_parent_subcategory](C:\Users\16462\Desktop\BootCamp\Module 1_Excel\Module 1 Challenge\Incorrect_parent_subcategory.png). After repeating the steps to recreate subcategories as described in bootcampspot, I was still getting the same parent categories while trying to reveal the subcategories. After careful anaylsis of each step via trial and error, I determined the missing step to correctly show the subcategories by choosing "skip column" under the parent category, while choosing "text" for the subcategories to be shown under the new column ![TCW_step3](C:\Users\16462\Desktop\BootCamp\Module 1_Excel\Module 1 Challenge\TCW_step3.png).
By inputting this missing additional step, I was finally able to show the subcategories ![subcategory_successful](C:\Users\16462\Desktop\BootCamp\Module 1_Excel\Module 1 Challenge\subcategory_ successsful.png) in order to input "plays" in my (COUNTIFS) code to have excel correctly run the calculations for each campaign outcome category ![COUNTIFS_coding_issue_plays](C:\Users\16462\Desktop\BootCamp\Module 1_Excel\Module 1 Challenge\COUNTIFS_coding_issue_plays.png).
I also relabeled the columns to the correct titles of "Parent Category" and "Subcategories" ![correct_labeling](C:\Users\16462\Desktop\BootCamp\Module 1_Excel\Module 1 Challenge\correct_labeling.png)
## Results
- What are two conclusions you can draw about the Outcomes based on Launch Date?
1.	Campaigns that started in the month of May resulted with the highest number of successful outcomes relative to the number of failed campaigns. After May, the number of successful theater outcomes begin to decline in each month after all the way through December.
2.	The last quarter of the year is not a good time to launch a play because it resulted with low successful campaigns that are close to the number of failed campaigns.
- What can you conclude about the Outcomes based on Goals?
Having a funding goal up to $4,999 resulted with the highest percentage of successful campaigns. As the funding goal increased, the percentage of failed campaigns gradually increased and the percentage of successful campaigns decreased. The ideal funding goal should not exceed $5,000 for the likelihood of a successful fundraising campaign. There were no canceled campaigns across the funding goal ranges.
- What are some limitations of this dataset?
1. The funding goal ranges established in the outcome vs. goals does not indicate what currency the ranges are in. Since the analysis of includes campaigns from all over the world with different currencies, the ranges may not accurately reflect its true value. In this analysis, the data neeeds to be filtered to specific countries to ensure the funding goal value is the same across the analysis.
2. The date range of the data spans from 2009-2017, which maybe considered outdated. More recent data from years 2018-2019 (excluding 2020 with the pandemic taken into consideration) should be considered for analysis.
- What are some other possible tables and/or graphs that we could create?
I recommend a pivot table presenting:
1. Launch date vs. percentage funded
2. Launch date vs. number of backers
A line graph presenting:
1. Funding goal vs. percentage funded
2. Funding goal vs. number of backers
