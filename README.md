# News-API

## Built By [Huguette UMUTONI)

## Description
News-API is a web application that displays a list of various news sources. On choosing a news source, it will preview the top news articles of the day. Clicking a news article will redirect the user to read it fully from the news source. It achieves this by using the [News API](https://newsapi.org/).

You can view the site at:[Heroku](https://emdeenews.herokuapp.com/)

## User Stories
These are the behaviours/features that the application implements for use by a user.

As a user I would like to:
*  see various news sources on the homepage of the application.
*  select a news source and see all news articles from the selected news source in the application.
*  see the image, description and the time a news article was created.
*  click on an article and read the full article on the source website.

## Specifications
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Display news sources | **On page load** | List of various news sources is displayed in a list |
| Display tabs with news by category | **On Tab link click** | Clickable links to open news based on category |
| Display articles from a news source | **Click a news source** | Redirected to a page with articles from the source |
| Display the preview of an article | **On page load** | Each article displays an image,description and publication date |
| To Read an entire article  | **Click an article** | Redirected to the news source's site to read the entire article |


## SetUp / Installation Requirements
### Prerequisites
* python3.6
* pip
* virtualenv
