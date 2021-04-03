# udacity

## Project One, Investigate a Dataset

## Introduction

The TMDB dataset provides data about movies: revenue, genres, directors, budget, popularity, release year, etc. The data is in numerical and text formats. 

From the data set notes: "The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time."

The questions I set out to answer:

<ol>

<li> <h3>Do actors matter?</h3>

What is the average revenue of all the movies in which actors appear? Does sample size matter? What about minimum number of appearances?

>The sample size and choice of minimum number of appearances matters quite a bit in investigating this question.

>For example, with a sample size of 100 movies and a minimum of 4 appearances, Orlando Bloom has the highest average revenue per movie in which he appears. 

>On the other hand, not limiting the sample (using all 2962 movies in the cleaned dataset) results in a more expected result, with Johnny Depp having the highest average revenue over the 30 movies he's appeared in, almost $300 million per movie.

>Overall this is a fairly good way to query actor's affect on the earnings of the movies in which they appear. Samuel L. Jackson has appeared in 40 movies, but his average revenue per movie is just under $200 million.


<li> <h3>Can you buy a high-revenue movie?</h3>

Does a higher budget generally mean that the movie will make more money?

>With a couple of outliers (high budget, low revenue or low budget, high revenue) there is a fairly strong positive correlation between budget and revenue, with a coefficient of .69.
>So yes, a higher budget tends to mean that a movie will make more money, but there are many other factors that may play a greater or equally important role.


<li> <h3>Could popularity predict revenue?</h3>

Can we predict revenue based on what we know about the popularity of a movie?

>There is a relationship between both the popularity (on social media) and the vote count and average (on this movie website) and revenue.

>It might be useful to train an AI to try to predict revenue given popularity scores.

<li> <h3>Genres and Budget Exploration</h3>

* What are the total budgets for each genre?

* What is the average budget for a movie in each genre?

* Which genre has the most movies in this dataset?

</ol>

