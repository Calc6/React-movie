# Assignment 1 - ReactJS app.

Name: Calum Cullen

## Overview.

Following the rubrix of "Baseline" due to circumstances. two static endpoints ,New Style added, watchlist added

### Features.
[ A bullet-point list of the __new features__ you added to the Movies Fan app (and any modifications to existing features) .]
 
+ Trending section
+ Upcoming section
+ WatchList section
+ etc
+ etc

## Setup requirements.

Setup should run just fine after being pulled down

## API endpoints.

[ List the __additional__ TMDB endpoints used, giving the description and pathname for each one.] 

e.g.
+ Trending Movies - /movies/trending#
  -Seperate page using TMDBs api that shows currently trending movies similar to the discover page. -      `https://api.themoviedb.org/3/trending/movie/day?api_key=${process.env.REACT_APP_TMDB_KEY}`

+ Upcoming Movies - /movies/Upcoming
  -Seperate page also displayed on the site header to show upcoming movies. Movies that are not currently released but that are soon. I did this using the TMDBs api also -`https://api.themoviedb.org/3/movie/upcoming?api_key=${process.env.REACT_APP_TMDB_KEY}&language=en-US&page=1`


## Routing.

[ List the __new routes__ supported by your app and state the associated page.]

+ /Watchlist - Similar to the favorites section allows the user to mark movies to add them to a watch later section
+ /movies/trending
+ /movies/upcoming

