# UCB-Excel-Project
# Kickstarting with Excel

## Overview of Project
I used advanced techniques in Excel like pivot table, V-lookup and graphing to analyze data from a crowdfunding platform Kickstarters. I used prescarpped dataset of ~4000 projects and 11 features like goal, pledged and outcomes.  

### Purpose
The purpose of the project is to help Louise, an upcoming playwriter to fund her play "Fever". She is estimating a budget of $10,000 and is understandably hesitant to jumping into her first fund raising campaign. We will use data insights to learn if there are specific factors that determine the success of a campaign. 

## Analysis and Challenges
I focused mainly on the theater catagory, plays subcatagory, launch date and goal amount to understand the sepcific factors that determine the sucess of a campaign.  
I feel there could be some other factors that were not captured in the data that might have played a role in the success of a capaign like status updates. Another challenge I felt that the data under subcatagory 1plays captured most campaigns in the $1000-$4999 range whereas Louise's budget was ~$10,000.

### Analysis of Outcomes Based on Launch Date
As we can see in the graph below that in the theater catagory, there are more successful campaign than the failed ones.  A very few of the campaigns got cancled. 

<img width="356" alt="Theater_Outcomes_vs_Launch" src="https://user-images.githubusercontent.com/69255270/111948382-4c9fbb80-8a9c-11eb-87f7-c5fcc6823261.png">

The most successful campaigns are in the month of May.  The possible explanation could be the start of summer as people plan their summer ahead of time.

There is a gradual decline in the success rate after May til September, in October again there is a slight increase in the sucessful campaign. A possible explaination could be people planning for the upcoming thanksgiving break in November. 

Looking at the analysis, I would recommend Louise to start the campaign in May. 

### Analysis of Outcomes Based on Goals
As we can see in the graph below that in less than $1000-$5000 range around 80% of projects in the subcatagory plays succeeded to meet their goals. 

<img width="304" alt="Outcome vs  Goals" src="https://user-images.githubusercontent.com/69255270/111948358-43165380-8a9c-11eb-9953-b826e0d5b7de.png">

The goal range $25,000-35,000 and $45,000 - greater than $50,000 have most failed campaigns around 80% and 100% respectively.

The range $35,000-$45,000 has again higher percentage of successful campaigns. 

Now talking about range around $10,000 that Louise is interested in, we see the difference in the successful and failed campaigns is only 10%. 

Overall, there is no trend and confirmed realtion between the success of a campaign and the goal .

### Challenges and Difficulties Encountered
Overall, It was a good data to work with.  I did see a clear trend bewtween the launch date and the success of a campaign. But there is no clear trend between the goal and the success of a campaing, and data is limiting in that aspect. To get the more understanding, I would like to see how people were engaged during the duration of the campaign,  were people updated on the progress of the projects? 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
1. The most successful campaigns are in the month of May, followed by october. This could be because of the reason that both these months come holidays and people when plan their holidays do search for plays.
2. Louise should lauch her campaign in the month of May and plan to perform it in the month of either June or July. 

- What can you conclude about the Outcomes based on Goals?
1. There is no clear trend in the goals and the outcomes of the campaigns. 
2. Based of the graph, Louise's goal of raising $10,000 is realistic and achievable as we can see goals higher than $10,000 ($35,000-$45,000) had successful outcome. 

- What are some limitations of this dataset?
1. Data didn't capture some of the other factors like "status update provided while the campaign waa active"
2. Most of the campaigns are in the goal range less than $10,000.

- What are some other possible tables and/or graphs that we could create?
1. Outcome vs. Pledged
2. Outcome vs.  Country 
