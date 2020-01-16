# Project Ideas

Ideas for future projects.


### URL Shortener
Simple CR(UD) microservice that returns a unique shortened URL that will redirect to the given URL in the request.

Challanges:
* Use a system that guarantees that every URL will always be unique.
* Performance must not be affected by a large amount of URL's.

Possible add-ons:
* Implement a user system with OAUTH verification that allows you to modify or delete the created URLS.
* Implement an analytics system where you store data about the browsers that requested the URL and how many times, also build an endpoint to allow verified users to access the stats.

### CRUD CMS System
Monolitic Wordpress look-alike CMS System that allows you to create blog posts, modify and delete them.

Challanges:
* This project is not a challange by itself but a portfolio project to show PHP expertise.

Possible add-ons:
* Implement your own comments system or add [Disqus](https://disqus.com/) support.
* Implement your own CDN system integrated in the project with full access to it.

### Rick and Morty Random Quote
Microservice that returns a [random quote](https://quotecatalog.com/quotes/tv/rick-and-morty/) of [Rick and Morty](https://en.wikipedia.org/wiki/Rick_and_Morty) series on every GET request.

Possible add-ons:
* Include on every response the author of the quote, the episode (and its name) and the season.

### Missed Anime Items Diagnoser (MAID)
Given an [Anilist](https://anilist.co/) profile, iterate through every single completed anime (or manga) item trying to find related animes that have an unspecified status and return the complete list of items.

Challanges:
* If you design this project as a microservice you will easily face timeout errors due to the ridiculous amount of requests to the [Anilist API](https://anilist.gitbook.io/anilist-apiv2-docs/) that will probably be needed to check the entire completed anime list (a complete list of 500 items could easily result in more than 3500 requests).
* This is be a good first approach to [GraphQL](https://anilist.gitbook.io/anilist-apiv2-docs/overview/graphql) API's.

Possible add-ons:
* Order priorities in the response list based on average score, item type (series, ova, ona, etc.) or user preferences based on request parameter. 

### Raw ideas to extend
  - TODO microservice list with email reminders
  - QUIZ microservice
