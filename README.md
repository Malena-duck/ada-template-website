Website https://malena-duck.github.io/success_movie/
# <center> Motivation </center>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;How can we produce a successful movie? _The script? The plot? The genre? Luck?_ And how has that changed over time? In this project we want to see how the movie characteristics have evolved over time. For instance, we will look at the main character, who are they? What is their gender? Age? Do those characteristics influence the success of the film? We will also look at other factors such as genre and runtime. Furthermore, the goal of this project is to discover correlations between the characteristics and success. For instance, what does the main character need to look like when it’s a romantic film vs an adventure film in order to perform well in the box-office? 


# <center> Research Questions </center>
1. How has the production of movies changed over time? What kind of features (genre, runtime, main character gender, etc) were in produced movies?
2. How have those features impacted the box office over time?
3. How well can we correlate production and success?
4. Using these insights, can we predict future production and/or the future box office of arbitrary productions?


# <center> The Data </center>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; We built our dataset from [CMU movies summary dataset](http://www.cs.cmu.edu/~ark/personas/), which contains diverse informations about the movies such as box office revenue, genre, release date, runtime, character descriptions, actors and synopsis. We completed this dataset using **Cinemagoer**, a python package for retrieving and managing the data of the **IMDb movie database**. This package was used to gain more complete information about the characters, the budget, box office, etc... We matched the IMDb movies to the Wikipedia ones using the titles of the movies and release date.

So now let's have a look at what our dataset.

## <center> The Evolution of the Production of Movies </center>

<p align="center">
  <img src="./assets/img/Movie_production_evolution.png" />
</p>

The dataset focuses on movies released before 2015. The increase in movie production in the last 30 years is also consistent with the global. With the boom in the number of movies made we have to wonder how the trends have changed throughout the years.

## <center> What Film Industry Are We Analyzing </center>

<p align="center">
  <img src="./assets/img/Countries_in_dataset.png" />
</p>

The movies contained in this dataset are overwhelmingly from the United States, followed by some from India and the U.K. Thus, the trends we find will reflect mainly the production of American movies. **So big Hollywood producers, make sure you pay extra close attention.**
<blink>Pay Attention</blink>


## <center> Distribution of Movie Genres </center>

<p align="center">
  <img src="./assets/img/genres_in_dataset.png" />
</p>

We can see that drama is the dominating genre in  this dataset. Is anyone really surprised that drama does not like to share the spotlight?




