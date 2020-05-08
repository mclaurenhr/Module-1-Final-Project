# Mircosoft Movie Studio

<img src='images/BlackPanther596d2f04d1540_2040.jpg'/>

## Introduction
Mircosoft wants to start a movie studio and they need some analysis conducted to determine what the best business strategy is for them to start this venture. They want more insight about the film industry and what type of movies are the most profitable. 

We decided to do an in-depth analysis on the sales trends of the movie industry and came up with three questions to explore in more detail to help shed more light into Mircosoft’s potential horizontal expansion project.   

## Data Description
<summary style="font-size: 22px"> List of Files</summary>

* group_data(5).csv


<details><summary style="font-size: 22px"> Question 1: What is the top overall movie genre?</summary>


We wanted take a deeper dive into exactly what the top movie genres were along with some additional sub questions to help with our analysis. A preview of the tables and visuals of the findings are attached below.

#### Tables Preview 
<img src= 'images/Total Genre Table.png'/>

#### EDA 
<img src= 'images/Genre count.png'/>



: Is there a correlation between release month and higher profitability in that genre?

#### Tables Preview 
<img src= 'images/Highest Month.png'/>

#### EDA
<img src= 'images/release month correlation.png'/>

#### Sub-Question: Is there a correlation between production budget and net profits in the that genre?

#### Tables Preview
<img src= 'images/Highest Net Month Table.png'/>
<img src= 'images/Domestic Net Mean Table.png'/>

<img src= 'images/hexin graph.png'/>

</details>

<details><summary style="font-size: 22px"> Question 2: What is the best day/month to release movies vs popularity/domestic net
</summary>

#### EDA
<img src= 'images/Release-Domestic Net.png'/>
<img src= 'images/Popularity and Day.png'/>
<img src= 'images/Net vs. Month.png'/>
<img src= 'images/month and popularity.png'/>



#### Sub-Question: Is there a correlation between runtime, budget, and season released?

#### Tables Preview 
<img src= 'images/Runtime vs. Domestic Gross Graph.png'/>

#### EDA
<img src= 'images/Runtime vs. Domestic Gross Table.png'/>
<img src= 'images/Runtime 100.png'/>

#### Sub Question: Is there a relationship of run time of movies vs domestic gross, popularity and production budget?

#### Tables Preview
<img src= 'images/Heatmap Table.png'/>

#### EDA
<img src= 'images/Heatmap.png'/>
</details>

<details><summary style="font-size: 22px"> Question 3: Can the film industry be a consistent profit center?</summary>


#### Table Preview
<img src= 'images/Table 1.png'/>

#### EDA
<img src= 'images/Num of Movies Graph.png'/>
<img src= 'images/Per movie data.png'/>
<img src= 'images/Ticket Sales Graph.png'/>
<img src= 'images/Production Budget.png'/>
<img src= 'images/ROI.png'/>
<img src= 'images/Profit Per Movie.png'/>
<img src= 'images/Correlation Matrix.png'/>
<img src= 'images/Net Profit Graph.png'/>
<img src= 'images/DD Net Profit.png'/>
<img src= 'images/DD Median ROI.png'/>
<img src= 'images/DD Median Domestic.png'/>



</details>


## Wrap Up
#### Interesting Findings
* The highest grossing movies average around 123 minutes while the lowest grossing movies average around the 95 minute mark. The most popular movies in the top 100 movies have a runtime of 149 minutes. If we take into consideration the most popular movies like Titanic, Avatar, and all the Marvel movies, this is what we would expect. As per our numbers, people normally like longer movies. Also as we can see in the heatmap that the correlation coefficient of runtime to production budget is positively correlated and is 0.31 which is moderately strong.

* Friday is the best day to release a movie, in terms of both popularity and also domestic gross. December is the best month to release a movie, in terms of both popularity and domestic gross.

**Figure 4.0 Boxplot of Net Profit in Millions** <br/> 
This figure shows a lot of information in a very condensed form. The body of the box shows the range of Net Profit for 50% of the data population and the line inside the box shows the median of the data. The whiskers on a normally distributed box plot demonstrate the values of 2.698 times the standard deviation and accounts for 99.3% of the data population. This is not a very clean distribution so the 2.698 times standard deviation will most likely account for a little less than 99.3% of the population.The longer the whiskers the more uncertain the outcome which is not good when trying to mitigate risk.

It should be noted that risk is not always a bad thing. If I mention left tail risk it means risk of losing money while right tail risk means higher reward possibility.

**Figure 4.1 Distribution of ROI**<br/>
This figure shows the distribution of the average return on investment for a movie in the 20 year timeframe we selected. The distirbution is fairly normalized around 50%. There seems to be a significant amount of right tail risk skewing the mean results. We know from previous data the median ROI for this same data is about 21% and the average of this entire data set is 23%. This distribution plot may not be the most useful.

**Figure 4.2 Distribution of Domestic Net Profit in Millions**<br/>
This figure shows the average profit per movie per year in millions. The KDE shows a distribution that looks relatively normal with a left shoulder and a right shoulder indicating two tail risk. 

**Figure 4.3 Distribution of Median ROI**<br/>
Looking at the median data tells a much scarier story when looking at return. This was also seen in the boxplot of net profits showing that the median ROI per year is near or ever below 0 indicating a loss. The outcomes are still very wide in rage, but this figure show us that chances are your movie will not make money in the domestic box office.

**Figure 4.4 Distribution of Median Domestic Net Profit**<br/>
Very similar picture as figure 4.3--scary. This shows that most movies do not make any profit and most actually lose money. 

#### Recommendations
1. The final recommendations to Mircosoft pertaining to what genre would be the most profitable for them to make movies in would be 'Action, Adventure, Sci-Fi'. We concluded this finding from the following analysis discoveries:

* Out of the top 100 domestic gross movies over the past 30 years, the genre 'Action, Adventure, Sci-Fi' made up the largest successful genre group in that data sample.

* Our findings showed that releasing 'Action, Adventure, Sci-Fi' movies in late Spring/early-mid Summer, Spring Break week, during the holidays, and if it is a cultural movie, released during that culture's Heritage month, all proved to be the most profitable times of the year to release that genre.

* Sticking to a production budget of 200 million dollars while producing an 'Action, Adventure, Sci-Fi' movie has proven to be the key ingredient to high net profitability that can be forecasted to be between 200-500 million dollars.


2. When it pertains to the length of the movie, averaging bewteen 120-150 minutes is the recommended time to ensure maximum profitablity.

3. Release movies on Friday due to higher views and in turn this will help drive up ticket sales as compared to other days. Set your release date to December to maximize gains and data has shown that it is better to push October or November release dates to December.

4. Even though the movie industry has shown great profits over the years, that has started to gradually decline. Our overall recommendation for Microsoft is to not enter the movie industry as an inexperienced content creator. We also believe this data has left out a major part of the revenue stream for movies in the on demand and streaming market. If we had data on the income generated from on demand services such as Netflix it may shed a much more positive light on becoming a content creator.


## Future Work
In the future I would like to create some projects on the following subjects:
* Finance and investment industry (predictive investment module)
* The real effects of COVID-19 on the economy and the future 
* Climate change over the past 10-25 years
