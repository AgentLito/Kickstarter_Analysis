# Kickstarter_Analysis
Overview of Project- Purpose
Louise’s play Fever just missed her Kickstarter fundraising goal of $2,885 by only $400. She ran her campaign for 28 days between June and July. Now Louise would like to know how other campaigns faired based on their goals and launch date. In our analysis of the Kickstarter data, we will take a deeper look at Theater campaigns and determine what factors such as the time of the year that a campaign is executed, and the amount of campaign goal played in successful Kickstarter campaigns. Our goal is to provide Louise with better insights to apply to her next Kickstarter campaign in an effort to be successful in future fundraising efforts.
The Creation Date of the Kickstarter campaigns dataset, we compared those time frames and if the campaign achieved its fundraising goal. Using pivot table, we can filter the data by Parent Category which allows us to look at all Theater projects within data set. Now we can look at the relation of successful and failed campaigns.
Parent	theater			
Years	(All)			
				
Count of outcome	Column Labels			
Row Labels	successful	failed	canceled	Grand Total
Jan	56	33	7	96
Feb	71	39	3	113
Mar	56	33	3	92
Apr	71	40	2	113
May	111	52	3	166
Jun	100	49	4	153
Jul	87	50	1	138
Aug	72	47	4	123
Sep	59	34	4	97
Oct	65	50		115
Nov	54	31	3	88
Dec	37	35	3	75
Grand Total	839	493	37	1369![image](https://user-images.githubusercontent.com/91812090/143730257-93ca442d-d257-4e83-b850-3d01865c39e8.png)

The months that had the most campaigns created and most successful were May and June.

This Illustration shows this.
![image](https://user-images.githubusercontent.com/91812090/143730422-6d81a540-f13d-40e4-b4f6-13358775d76d.png)
Analysis
This is the formula we used
=COUNTIFS(Kickstarter!D$84:D$4108,">=1000",Kickstarter!D$84:D$4108,"<5000",Kickstarter!F$84:F$4108,"successful",Kickstarter!P$84:P$4108,"plays")

Goal	Number Successful	Number Failed	Number Canceled	Total Projects	Percentage Successful	Percentage Failed	Percentage Canceled
Less than 1000	141	45	0	186	76%	24%	0%
1000 to 4999	388	146	0	534	73%	27%	0%
5000 to 9999	93	76	0	169	55%	45%	0%
10000 to 14999	39	33	0	72	54%	46%	0%
15000 to 19999	12	12	0	24	50%	50%	0%
20000 to 24999	9	11	0	20	45%	55%	0%
25000 to 29999	1	4	0	5	20%	80%	0%
30000 to 34999	3	8	0	11	27%	73%	0%
35000 to 39999	4	2	0	6	67%	33%	0%
40000 to 44999	2	1	0	3	67%	33%	0%
45000 to 49999	0	1	0	1	0%	100%	0%
Greater than 50000	2	14	0	16	13%	88%	0%![image](https://user-images.githubusercontent.com/91812090/143730568-cd3ef7dd-1285-4f85-a991-855450a78e38.png)
![image](https://user-images.githubusercontent.com/91812090/143730587-5a584f71-d253-4bbc-8502-3acdf5651b22.png)

Challenges and Difficulties Encountered
Working with a large dataset like Kickstarter, huge challenge was filtering the data making sure its understood and interpreted. Once filtered correctly. Several times the data did not reflect what we expected. We have to make several adjustments to the formula. We reviewed the formula and resolved the issues.
Results:
What are two conclusions you can draw about the Outcomes based on Launch Date?
In conclusion May and June are the best months to start a Kickstarter campaign. May and June had the most Plays campaign started. Which were the most successful. The data shows that May-August had the most campaigns started. Our chart clearly shows the trend where te campaign becoming less successful after June.
What can you conclude about the Outcomes based on Goals?
We concluded that the campaign had goals less than $5000 were the most successful. More campaigns launched where goals were less than $5000.
What are some limitations of this dataset?
It would have been more eye opening if we had more data. Like what type of advertising and marketing for each campaign.This could have factored fails and successes.
What are some other possible tables and/or graphs that we could create?
Within the filtering data, Play campaigns ran 30 days had the most success
Plays that ran 30 days had goals less than $5000
The data provided shows Plays campaign with Goals of Under $5000 of 30 days in Length Launched in May or June had the most success. Best practices would be to study this data for future campaigns.

