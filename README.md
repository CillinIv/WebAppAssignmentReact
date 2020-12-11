# WebAppAssignmentReact
This is the Repository for my WebAppDev assigment
# Assignment 1 - ReactJS app.

Name: Cillin Ivory

## Features.

...... A bullet-point list of the ADDITIONAL user features you have implemented for the  Movies Fan app ......,
 
 + Feature 1 - A similar movies added to the movie details to show movies that are similar to it. 
 + Feature 2 - Added an upcoming page which displays upcoming movies. These may intrest people to see what movies are becoming popular
 + Feature 3 = Added a top rated page to show the highest rated movies. This displays movies that people have voted to be the best
 + Feature 4 = Added a trending page to show trending movies. These movies are movies that are currently trending. Users  may be intrested in moveis which are popular at the momment.
 + etc

## Setup requirements (If required).

...... A brief explanation of any non-standard setup steps necessary to run your app/client locally (after cloning the repo) ........

## API Data Model.

..... List the additional TMDB endpoints used in your assignment, e.g.

+ https://api.themoviedb.org/3/movie/upcoming - gets a list of upcoming movies.. 
+ https://api.themoviedb.org/3/trending/movie/week - gets a list of movies trending over the week
+ https://api.themoviedb.org/3/movie/top_rated - gets a list of the top rated movies.
+ https://api.themoviedb.org/3/movie/${id}/similar - gets movies similar to id entered.

## App Design.

### Component catalogue (If required).

....... Insert a screenshot from the Storybook UI, hi-light stories relating to new/modified components you developed - see example screenshot below] .......

![][stories]

### UI Design.

...... Insert screenshots of the new/modified views you have added to the Movies Fan app. Include a caption for each one clearly stating its purpose and any user interaction it supports ........

![][movieDetail]
>Shows detailed information on a movie. Clicking the 'Show Reviews' button will display extracts from critic reviews.

![][review]
>Shows the full text for a movie review. 

## Routing.

...... Insert a list of the additional routes supported by your Movies Fan app. If relevant, specify which of the routes require authentication, i.e. protected/private.

+ /movies/favorites (protected) - displays the user's favorite movies selection.
+ /reviews/:id (public) - displays the full text of a movie review.
+ etc.
+ etc.

### Data hyperlinking.

.... Use screenshots to illustrate where data hyperlinking is present in your views - include captions.

![][cardLink]
> Clicking a card causes the display of that movie's details.

![][reviewLink]
>Clicking the 'Full Review' for a review extract will display the full text of the review

## Independent learning (If relevant).

. . . . . Briefly mention each technologies/techniques used in your project codebase that were not covered in the lectures/labs. Provide source code filename references to support your assertions and include reference material links (articles/blogs).

---------------------------------

[model]: ./data.jpg
[movieDetail]: ./public/movieDetail.png
[review]: ./public/review.png
[reviewLink]: ./public/reviewLink.png
[cardLink]: ./public/cardLink.png
[stories]: ./public/storybook.png
