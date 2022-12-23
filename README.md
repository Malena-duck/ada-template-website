Website https://malena-duck.github.io/success_movie/
# <center> Motivation </center>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;How can we produce a successful movie? _The script? The plot? The genre? Luck?_ And how has that changed over time? In this project we want to see how the movie characteristics have evolved over time. For instance, we will look at the main character, who are they? What is their gender? Age? Do those characteristics influence the success of the film? We will also look at other factors such as genre and runtime. Furthermore, the goal of this project is to discover correlations between the characteristics and success. For instance, what does the main character need to look like when it’s a romantic film vs an adventure film in order to perform well in the box-office? 
&nbsp;  

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

The movies contained in this dataset are overwhelmingly from the United States, followed by some from India and the U.K. Thus, the trends we find will reflect mainly the production of American movies. 

**<center> So big Hollywood producers, make sure you pay extra close attention. </center>**
<p align="center">
  <img src="./assets/img/pay_attention.jpg" width = 250/>
</p>
&nbsp;  
&nbsp;  


## <center> Distribution of Movie Genres </center>

<p align="center">
  <img src="./assets/img/genres_in_dataset.png" />
</p>

**And Drama takes the spotlight!!! Shocker!**
We can see above drama is the dominating genre in this dataset, followed by comedy and romance. Stay tuned to see if a Drama movie is actually the most profitable.



# <center> The Production of Movies throughout the Ages </center>

<center> Let's examine some features in films and how they have evolved. </center> 
## <center> Runtimes </center>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;We know that at the beginning of the 20th century, in the early days of Cinema, films were short in runtime due to technological limitations. However by the 1920s, technology had advanced enough to accomodate feature-length films. The sky became the limit when it came to runtimes. So what length did directors and producers gravitate towards?


<p align="center">
  <img src="./assets/img/Runtime_evolution.png" />
</p>

(new graph needed ED)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Around the 1915s we can see there was variation in runtime duration with a few ups and downs ocsillating around 60 minutes. As time went on however we can see a steadily increase in film duration until the 1960s where the median duration of films plateaued around 100 minutes and has remained there ever since. Take note that the 25th and 75th quantiles (grey area) also plateaued with the median. 

So nowadays movies have little variation in their runtime, but can we be sure it is the right one?

## <center> Genres Production </center>


<p align="center">
  <img src="./assets/img/Movie_genres_evolution.png" width = "600" />
</p>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The popularity of producing black and whites died off as the years went by which is not surprising. We can also see that drama has been the most produced genre each year consistently. At least that was the case until recently! Since 2012 there has been a rise in popularity in other genres such as fantasy, horror, adventure, with thriller and adventure dominating the production. The sudden change in trend from consistently having drama as number one to a range of different genres becoming popular and vastly varying from year to year is quite interesting, this could perhaps be attributed to the shift that Marvel movies brought to the Cinema industry.


## <center> Main Character </center>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Who is the main character? How have they changed through time? 
&nbsp;

Let's first have a look at the proportions of male vs female main characters:
<p align="center">
  <img src="./assets/img/Gender_proportion_main_characters.png" />
</p>

Men are more often the main character than women, though this was not always the case in the early 1920s as seen in the figure above. We can see that the percentage of male leads has increased over time and then oscillated around a maxima.

<p align="center">
  <img src="./assets/img/Female_height.png" width="350"/>
  <img src="./assets/img/Male_height.png" width="350"/>
</p>

<p align="center">
  <img src="./assets/img/Female_main_chara.png" width="350"/>
  <img src="./assets/img/Male_main_chara.png" width="350"/>
</p>


&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Our analysis of who is the main character gave us the following information:
It seems that for women the main character's height preference has been between 1.6m and 1.72m throughout the years, while for men it seems the interval has decreased with time. From 1.75m to 1.9m before the 1940s to the chosen height being between 1.75m and 1.85m. When it comes to women, we can see that the age rarely exceeds 40 years old. It seems women between the ages of 25 and 30 have usually been the chosen main characters. However, this is not the case for men. Men have a larger, not to mention older, interval between the ages of 30 and 50 years old. Both male and female main characters used to be younger before the 1940s.



# <center> An Analysis of various features' impact on the Box-office throughout Time  </center>


<p align="center">
  <img src="./assets/img/Box_office_inflation.png" />
</p>

We can see that 


<p align="center">
  <img src="./assets/img/Budget_inflation.png" />
</p>

We can see that the budget of films has been steadily rising until recent years where it sky rocketed! This sudden change also matches the timeline for when Drama was dethroned from its number 1 spot as most produced genre each year.

<p align="center">
  <img src="./assets/img/rocket.jpg" width = "100"/>
</p>













