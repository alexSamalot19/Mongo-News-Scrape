# Times Scraper

<br>

## Description

Times Scraper is a blog and news scraper that collects data from the New York Times. Recent articles are added to the article database when the button is clicked. Articles and comments can be deleted individually.

<br>

## Overview of App Organization

This is app contains the following files:

```
Mongo-News-Scrape
  - .gitignore
  - models
    - Article.js
    - index.js
    - Note.js
  - node_modules
  - public
    - app.js
    - index.html
  - package.json
  - server.js
```

<br>

## Run Instructions

The looks as it is displayed below:

![StartPage](public/img/StartPage.png)

The user can fill out and delete comments on individual articles.
Recent articles can be added with the Click Me button.

## This App Utilizes

- [Node](https://nodejs.org/en/about/)

- [MongoDB](https://www.mongodb.com/)

- [Cheerio](hhttps://www.npmjs.com/package/cheerio)

<br>

## Role in Development

My name is Alex I am a bootcamp student whose portfolio can be found
[here](https://alexsamalot19.github.io/Samalot-Alexander-Portfolio/).

I designed this app using existing APIs and packages listed in the **This App Utilizes** section. I used Node and Sequelize to query and route data in this app, and Cherrio to scrape the NYT website. The site is deployed to Heroku [here](https://news-scrape9.herokuapp.com/).
