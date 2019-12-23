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

The user begins at:

![StartPage](public/assets/img/StartPage.png)

The user can fill out the **Burger Name** form,

![OrderInput](public/assets/img/OrderInput.png)
![AsOrder](public/assets/img/AsOrder.png)

The burger name appears on the left side above the form until the **Devour** button is clicked

![AsDevoured](public/assets/img/AsDevoured.png)

This moves the selected burger to the right column on the screen designated for devoured burgers

## This App Utilizes

- [Node](https://nodejs.org/en/about/)

- [MongoDB](https://www.mongodb.com/)

- [Cheerio](hhttps://www.npmjs.com/package/cheerio)

<br>

## Role in Development

My name is Alex I am a bootcamp student whose portfolio can be found
[here](https://alexsamalot19.github.io/Samalot-Alexander-Portfolio/).

I designed this app using existing APIs and packages listed in the **This App Utilizes** section. I used Node and Sequelize to query and route data in this app, and Cherrio to scrape the NYT website. The site is deployed to Heroku [here](https://news-scrape9.herokuapp.com/).
