# ICT Skills 2 Assignment.

Name: [your name]

## Overview.

[ A paragraph on your React app's concept followed by a bullet-point list of its feature set - only list new/modified features if you are expanding the Movies app. ]
 
+ Feature 1
+ Feature 2
+ Feature 3
+ etc
+ etc

## Setup requirements.

[ Briefly state (to a third party) the setup steps necessary to run your app/client locally, e.g. .env and any other config files.]

## App Design.

### Routing/Navigation.

[List the set of routes your app supports - only mention new instances if you expanded the Movies Fan app. State the view linked with each route.] 
e.g.
+ /movies/:id - detailed information on a specific movie.
+ /movies/upcoming - lists movies soon to be shown in cinemas.
+ etc.
+ etc.

### Views/Pages.

[ For each view in your app, show a screenshot and caption  of each view in your app - only new/modified ones in the case of the Movies Fan app. If necessary, use multiple screenshots for a view to demonstrate its full capability.

e.g.
>Lists movies from the Discover endpoint. Allows filtering on title and genre attributes.

![][d1]

![][d2]

>Shows detailed information on a specific movie

![][detail]


#### Component catalogue.

[ Use the Storyboook UI to highlight the new components for which you developed stories.]
e.g.
![][stories]

## Caching.

[ List the TMDB server state the app caches - additional to that covered in the labs. Include a screenshot(s) of the react-query dev tools to validate your list]
e.g.
+ Discover movies (pagination support)
+ Movie details
 + etc
+ etc

![][caching]
## Authentication (if relevant).

[Briefly state how you implemented authentication for the app, e.g. basic, Firebase, etc. Also, list the routes that are private/protected.]

+ /reviews/:id
+ /movies/favourites

## Server-side persistence (if relevant)

[ Briefly state the persistence 
platform your app uses (e.g. TMDB lists, Firestore) and itemize the data it persists.]

## Additional features,

[Briefly state any additional features of your app that may not be obvious from the previous sections, e.g. pagination, extended filtering/sorting, searching.]

## Independent learning,

[Briefly explain any aspects of your assignment work that required independent learning/research on your behalf., e.g. 3rd-party components, libraries, tools. Include source code references.]

### Design patterns.

Briefly state the application of any composition design pattern (i.e. Render props, Container) in your codebase. Distinguish between those relating to the reuse of patterns already implemented in the labs (e.g. TemplateMoviePage) and new occurrences. Code excerpts art NOT necessary.

[d1]: ./public/discover1.png
[d2]: ./public/discover2.png
[dtl]: ./public/detail.png

[view]: ./view.png
[stories]: ./storybook.png