https://medium.com/@alihu.alhassan/analysis-of-the-indian-startup-funding-data-b66a2d45c352

Analysis-of-the-Indian-Startups-Funding-Data

Ideas, creativity, and execution are essential for a start-up to flourish. But are they enough? Investors provide start-ups and other entrepreneurial ventures with the capital---popularly known as "funding" to think big, grow rich, and leave a lasting impact.
This article will explore the results of analyzing the Indian startup funding dataset which contains information on funding received by start-ups in India from 2018 to 2021. The data for each year of funding contains information such as the startups' names, locations, the funding amounts received, the sectors in which they operate, and the investors' information.
This Analysis of the Indian Startup Funding Data seeks to analyze and understand the dataset to discover exciting trends that will help in various decision-making. We will glean insight from this dataset by answering the following questions.
1.	Which year has seen the most funding in terms of the number of startups funded?
2.	Which year has seen the most funding in terms of funding amount?
3.	How much funds do startups generally get in India?
4.	What type of funding do startups in India generally receive?
5.	Which cities get the highest number of startups and most funding from investors?
6.	Which industries get more funding?
The following hypothesis will also be tested

H0: Startup location has no relation to it getting funding/ Startup location has no relation to it receiving funding.
H1: Startup location and number of funding are positively correlated.

H0: There is no relation between the funding amount and the stage of funding.
H1: The funding amount is positively related to the stage of funding.

Detailed steps of the data processing and cleaning steps can be found in the jupyter notebook here.

Analysis & Visualization

From the analysis, the number of startups funded fell from 526 in 2018 to 89 in 2019. It then rose to 1052 in 2020, then rose again to 1206 in 2022. The year 2022 is therefore the year with the highest number of startups getting funding.
In line with the trends in the number of startups funded, 2021 had the most funding followed by 2020, with a total of $ 91,359,563,655 invested. 2018 had the third highest with 2019 having the least amount invested in Indian startups. These figures are consistent and directly correlated with the number of startups funded.
Over the 4years, the amount received on average by startups in India was $97,859,791.87. The average funding amount increased year on year from 2018 to 2022. It can be observed that Indian startups are very attractive to investors as the average investment received keeps increasing year on year. However, there is a large spread between the minimum funding of $876 and the maximum funding of $150,000,000,000
In terms of funding stages, seed funding is the highest type of funding over the 4 years followed by Series A funding.  Pre-series A, Series B, and Series C funding are among the top 10 stages of funding. Although the number of undisclosed funding exceeds any form of funding. 
From the word cloud, Bangalore is the city with the highest number of startups, followed by Mumbai and Gurugram. The concentration of startups in these cities may be a result of them being major cities.
In terms of the investment amount, Mumbai is the city with the highest amount of funding at $231494372742. Bangalore is in a distant second with $24871950210 and Gurugram city third with $5581118500.
The analysis reveals that the Fintech sector is the sector with the highest number of startups funded (260), followed by the Edtech sector with 222 startups, E-commerce has 117 startups whiles the healthcare sector has 95 startups.
 
Hypothesis Testing

The first hypothesis tested is the null hypothesis that “Startup location has no relation with it getting funding/ Startup location has no relation with it receiving funding”. It alternative hypothesis is that “Startup location and number of funding are positively correlated”. The regression analysis revealed that the variables are NOT correlated hence there is no relationship between location and funding amount. 
The second null hypothesis also tested for a relationship between funding amount and the stage of funding. The analysis again revealed that there is no direct relationship between the variables.
The link to the full article with visualization can be seen at the link below.


https://medium.com/@alihu.alhassan/analysis-of-the-indian-startup-funding-data-b66a2d45c352
