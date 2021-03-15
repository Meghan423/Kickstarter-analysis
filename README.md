# An Analysis of Kickstarter Campaigns
---
## Overview of Project:

Our client for this analysis is trying to raise funds for a new theater production. She is seeking insights from kickstarter data in order to help her make actionable, data-driven decisions aimed at a successful campaign. Using this data set, we aim to get a stronger idea of what makes a successful fundraising campaign by pulling out information like the best times of year to run a campaign and reasonable fundraising goals. 

---
## Analysis and Challenges:

Using the Kickstarter data, we first needed to drill down to the most relevant data set through filtering. By filtering categories to hone in on theater and the subcategory of plays and remove kickstarter information for other types of projects, we can get a clearer view of the success rates of campaigns similar to our own. From there we set out to determine two key categories of outcomes: Those based on monetary goals and those based on timing. 

Before we could do either of these things we needed to clean up and parse out the data. The data provided included goal amounts, the total pledged, and the backers count (total individuals who donated). Using that information, we could then create formulas to determine the percentage of the goal funded via the campaign along with the average donation. 

We also added formulas to convert the campaign launch and deadline information into readable and usable dates. 

### Outcomes Based on Goals

To provide insight into achievable fundraising goals, the data was broken out into financial brackets ranging from less than $1,000 up to greater than $50,000 in $5,000 increments. We then used the outcomes column to sort and count campaigns with the three labels: Successful, Failed, and Canceled. Once these numbers were sorted and totaled we were able to formulate the percentages of each category giving us insight into the success rates of campaigns based on their initial fundraising targets. One challenge encountered in this sheet was creating a formula that accurately presented the percentage. When I originally changed the column category to percentage it gave me 7600% instead of 76%. After talking through with a TA, I was able to figure out how to tweak the formula to accurately present the data as needed. 
	
### Outcomes By Launch Date

To provide insight into the ideal time to launch a campaign, we again used the outcomes data to sort successful, failed, and canceled campaigns by time of year. More specifically, we can see the rate of successful campaigns based on the month they launched. A potential challenge here would be if one did not know how to alter the timestamp information into an actionable date.

---
## Results

### Theater Outcomes by Launch Date

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/80495032/111089132-e1387580-8500-11eb-809f-e38d6ed300f3.png)

Based on when the majority of successful campaigns occurred on Kickstarter we can see that May would be the ideal time to launch a campaign. 
However, this seems to also track with rate of activity. That is to say, more campaigns occur during these months so naturally there are more successful campaigns in these months. So, yes, it is a good idea to launch in May but it is not a guarantee for success. 

### Outcomes based on Goals 

![Outcomes_VS_Goals](https://user-images.githubusercontent.com/80495032/111089094-ad5d5000-8500-11eb-8518-c6dd9c4881c1.png)

Given the data, success rates seem to be more successful with lower goal amounts. The higher the amount the higher the failure rate. This doesn’t hold precisely true in some of the higher amount goal levels, but that is balanced with much smaller data sets for those ranges. With the data provided, our strongest chance of success is setting a goal of $5,000. 

### Limitations

Not included in this are other information points that could be pulled from the data. For example, pulling the descriptive statistics to drill further into the exact amounts pledged in a successful campaign makes for a stronger argument of why the $5,000 goal amount is a solid choice. Additionally, we could add more filters to the outcomes data to contrast outcomes by geographical location. Unfortunately, while the data set for Kickstarter campaigns in general is quite large, when we drill down to play productions in the geographical location where our client is launching their play, our numbers become much smaller, limiting the quality of our analysis. Another piece of information we could look into is how the duration of a campaign impacts the outcome to help us determine the ideal length of a campaign. 

