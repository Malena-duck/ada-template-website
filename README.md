# <center> Motivation </center>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;How can we produce a successful movie? _The script? The plot? The genre? Luck?_ And how has that changed over time? In this project we want to see how the movie characteristics have evolved over time. For instance, we will look at the main character, who are they? What is their gender? Age? Do those characteristics influence the success of the film? We will also look at other factors such as genre and runtime. Furthermore, the goal of this project is to discover correlations between the characteristics and success. For instance, what does the main character need to look like when it’s a romantic film vs an adventure film in order to perform well in the box-office? MARIN




# <center> Research Questions </center>
1. How has the production of movies changed over time? What kind of features (genre, runtime, main character gender, etc) were in produced movies?
2. How have those features impacted the box office over time?
3. How well can we correlate production and success?
4. Using these insights, can we predict future production and/or the future box office of arbitrary productions?


# <center> The Datasets </center>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; We built our dataset from [CMU movies summary dataset](http://www.cs.cmu.edu/~ark/personas/), which contains diverse informations about the movies such as box office revenue, genre, release date, runtime, character descriptions, actors, summary and language. We completed it using **Cinemagoer**, a python package for retrieving and managing the data of the **IMDb movie database**. This package is used to gain more complete information about the characters in each movie in order to maximise the accuracy rate when finding the main character, as the IMDb database is more complete. We matched the IMDb movies to the Wikipedia ones using the titles of the movies and release date.

<p align="center">
  <img src="./assets/img/trial.png" />
</p>


<center> ![alt text for screen readers](zebra.jpg "trial1") </center>
