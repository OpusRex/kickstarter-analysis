# An Analysis of Kickstarter Campaigns
## Description:
### Challenge 1
1. **Campaign Goals**
  - Figure 1A represents the campaign outcome percentages based on set goals ($) for subcategory “***plays***”. The overall trends in Figure 1A suggests that:
    *	There is a big difference between the successful and failed campaign percentages when the set goal is less than $5,000, or more than $45,000. The successful campaigns are more likely when the set goal is less than $5,000. Successful campaigns appear less likely when the set goal greater than $45,000.
    * Between $5,000 and $50,000 goal, there is no specific trends between the outcome and goals.
    * There are no canceled campaigns for “***plays***” subcategory.
    * Currency types are not consistent for all plays.
  
  ![Figure%201A](Challenge1-Figure%201A.png)

- Figure 1B represents the campaign outcome percentages based on set goals ($) when no filter on parent categories or subcategories is applied. The overall trends in Figure 1B suggests that:
  * The successful campaigns  are less likely as the goal increases.
  * The canceled and unsuccessful campaigns are more likely as the goals increases.
  * There is a large variance between the successful and failed campaigns when the set goal is less than $5,000, or more than $45,000.
  * Currency types are not consistent for all plays.
  
  ![Challenge1-Figure%201B](Challenge1-Figure%201B.png)

- The interpretations from Figure 1A and 1B suggest the campaign goal can affect the final outcomes. Campaign goal which are lower are more likely to have a successful outcome.

2. **Campaign Launch Date**
- Figure 2 shows the campaign outcomes in each month for parent category “***theater***”. 
  * The number of successful campaigns varies among different months. “*May*” has the highest number of successful campaigns while “***December***” shows the lowest.
  * The failed and cancelled campaign trends seem steadier among different month compared to successful campaigns.
  * Overall, the number of successful campaigns in each month is higher than each of failed and canceled campaigns.
  
  ![Challenge1-Figure%202](Challenge1-Figure%202.png)
<br/>
<br/>
This dataset is a very good starting point for analysis about future crowdfunding campaigns. However, there are some limitations to it including but not limited to: sample size, lack of information about crowdfunding method and advertisement type, and lack of details on backers of each parent category/subcategory-which could let the analyzer know his/her audience better, and invest on the right people for his/her campaign goals.

<br/>
The data suggests that converting the currencies to a base currency(i.e. U.S. Dollars) will give more accurate results. Also, filtering the data based on country may lead to interesting results as the culture, industry, economy and etc is different for each country. Investigating the gap between the goal and pledged columns could also help the analyzer decide to what extent a campaign failed.
