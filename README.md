# PROJECT OVERVIEW : MICROSOFT MOVIE STUDIO

> The objective of this project is to explore the film industry inorder to identify the types of films that are currently performing well at the box office by conducting in-depth analysis of the industry with the aim of finding valuable and actionable insights that will guide Microsoft as they make decisions on the type of films to create in their new movie studio.

## BUSINESS PROBLEM
---

> Microsoft has seen an opportunity in the film industry as creating original video content is becoming popular across all big companies. They currently lack the know how of the type of films that are performing well at the box office and need to understand the factors that contribute to a successful film. The business problem is therefore studying films that are performing well and drawing insights from them to guide the decision making process of the types of films to be produced at their new movie studio.

## DATA COLLECTION
---

> We used publicy available information from reputable box office databases that provide comprehensive data on film performace metrics. We have listed the databases we shall use in our analysis below:

1. [Box Office Mojo]("https://www.boxofficemojo.com/")
2. [IMDBLinks]("https://www.imdb.com/")
3. [Rotten Tomatoes]("https://www.rottentomatoes.com/")
4. [TheMovieDB]("https://www.themoviedb.org/")
5. [The Numbers]("https://www.the-numbers.com/")

## DATA ANALYSIS
---
We utilised the following libraries for our analysis
1. Pandas
2. Matplotlip
3. SQLite3

We used Exploratory Data Analysis to gain insights, identify patterns and understand the characteristics of the data; this helped in formulating hypotheses, generating ideas and making data-driven decisions.

Data cleaning: we have explored various ways in cleaning the data provided which includes and not limited to handling missing values, outliers, and inconsistencies. This ensures that the data used for analysis is accurate and reliable.

Data visualization: We have used data visualisation techniques such as bar graphs, line graphs and scatter plots to visually explore the data and identify trends, outliers, and patterns. Visualization helps in gaining a deeper understanding of the data and communicating findings effectively.

Data relationships: We have employed EDA in identifying relationships between variables by analyzing correlations and scatter plots. This helps in understanding the interactions between variables and their impact on the data.

## RESULTS
---
1. Movies with higher budgets have shown a corresponding increase in the revenues;
<img width="401" alt="image" src="https://user-images.githubusercontent.com/128212536/232332846-19022157-4cef-4aa1-8dfd-47e6e46816cc.png">

2. The genres Animation, Family, Adventure and Fantasy have the highest profits;
<img width="573" alt="image" src="https://user-images.githubusercontent.com/128212536/232332879-9a7fcf7a-3aa3-442f-89bf-51e2ead3687a.png">

3. Top 4 most produced genres are Drama, Thriller, Action and Adventure;
<img width="566" alt="image" src="https://user-images.githubusercontent.com/128212536/232332891-b114df9e-36fb-49bf-9577-a716095a8730.png">

4. Top 4 genres with the highest average ratings are Historical, Documentaries, Animation and Music;
<img width="564" alt="image" src="https://user-images.githubusercontent.com/128212536/232332901-51af741b-d5ba-4d89-ba32-10bdca7959aa.png">

5. The genres Animation, Adventure, Fantasy and Family are the top genres with low production costs but with high profits;
<img width="569" alt="image" src="https://user-images.githubusercontent.com/128212536/232333078-0b40a1cf-bc10-45ea-aef6-233df8c5d902.png">

6. The average runtime for the most profitable movies is 105 minutes.

7. The most popular language with highest profits is English.


## RECOMMENDATIONS
---
1. Microsoft Movie Studios should produce movies that cut across the Animation, Adventure, Family and Fantasy so as to optimise profits as they are the most profitable genres, they are also the genres with low production costs and high profits.

2. Microsoft Movie Studios should produce the movies in English as it's the most popular language in the box office and have the highest profits; they can traslate them to France, Hindi to capture top international markets.

3. Microsft Movie Studios films should have an average runtime of 105 minutes as this is the most common time among the top earning movies.

## NEXT STEPS
---

1. Create a Machine Learning algorithm that can predict the optimal budget, genre and duration to create a movie that generates the highest profits. 

2. We can further dig into the data and fetch best writers, editors, actors and such personell to create awesome movies

 


