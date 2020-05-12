# Mircosoft Movie Studio

<img src='images/BlackPanther596d2f04d1540_2040.jpg'/>

## Introduction
Mircosoft wants to start a movie studio and they need some analysis conducted to determine what the best business strategy is for them to start this venture. They want more insight about the film industry and what type of movies are the most profitable. 

We decided to do an in-depth analysis on the sales trends of the movie industry and came up with three questions to explore in more detail to help shed more light into Mircosoft’s potential horizontal expansion project.   

## Data Description
<summary style="font-size: 22px"> List of Files</summary>

* group_data(5).csv
* bom.movie_gross.csv
* name.basics.csv
* title.akas.csv
* title.basics.csv
* title.crew.csv
* title.principals.csv
* title.ratings.csv
* tmdb.movies.csv
* tn.movie_budgets.csv


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
 * In the top genre findings, the outlier, Black Panther, followed a different pattern from the other top box office movies of all time that resulted in being one of the highest grossing movies of all time. 

#### Recommendations
1. The final recommendations to Mircosoft pertaining to what genre would be the most profitable for them to make movies in would be 'Action, Adventure, Sci-Fi'. I concluded this finding from the following analysis discoveries:

* Out of the top 100 domestic gross movies over the past 30 years, the genre 'Action, Adventure, Sci-Fi' made up the largest successful genre group in that data sample.

* Our findings showed that releasing 'Action, Adventure, Sci-Fi' movies in late Spring/early-mid Summer, Spring Break week, during the holidays, and if it is a cultural movie, released during that culture's Heritage month, all proved to be the most profitable times of the year to release that genre.

* Sticking to a production budget of 200 million dollars while producing an 'Action, Adventure, Sci-Fi' movie has proven to be the key ingredient to high net profitability that can be forecasted to be between 200-500 million dollars.


2. When it pertains to the length of the movie, averaging bewteen 120-150 minutes is the recommended time to ensure maximum profitablity.

3. Release movies on Friday due to higher views and in turn this will help drive up ticket sales as compared to other days. Set your release date to December to maximize gains and data has shown that it is better to push October or November release dates to December.

4. Even though the movie industry has shown great profits over the years, that has started to gradually decline. Our overall recommendation for Microsoft is to not enter the movie industry as an inexperienced content creator. We also believe this data has left out a major part of the revenue stream for movies in the on demand and streaming market. If we had data on the income generated from on demand services such as Netflix it may shed a much more positive light on becoming a content creator.


## Future Work
  1. Further Optimization correlations to reduce costs
   * Which genres are the cheapest to make?
   *  Are experience directors and actors really need to make money?
   * Evaluate box office success of inexperienced movie studios
  2. Evaluate the revenue generated from streaming services such as Netflix
   * A big portion of the revenue is missing from film studios by only looking at box office data. I would like to see what the total revenue streams of this business is.
   * Adding in inflation data to this to see what the true box office dollars are to get a better look at ticket sale dollars over the years
