# ⭐ Object-Relational Mapping: E-Commerce BackEnd ⭐
    
![Contributor](https://img.shields.io/badge/Contributor-Hanbyeol(Justin)Lee-purple)
[![License](https://img.shields.io/badge/License-MIT-blue)](https://opensource.org/license/MIT)
![ORMLibrary](https://img.shields.io/badge/ORMLibrary-Sequelize-yellow)
![DataBase](https://img.shields.io/badge/DataBase-MySql2-green)
![Security](https://img.shields.io/badge/Security-Dotenv-magenta)
![RouteApplication](https://img.shields.io/badge/RouteApplication-Express.js-red)

## Outcome

Followings are the outcomes of the challenge 13:

* A walkthrough video demonstrating the functionality of the application and all of the acceptance criteria being met. </br>
[Walk-Through Video: Webm file](https://drive.google.com/file/d/1DesRcjh71bOVOYdFWXmtrp2ilY5Ni-Oo/view) </br>
[Walk-Through Video: GIF file](https://github.com/justinsta624/MeetyourSVGMaker/blob/main/outcome/231210_Walk-Through-Video_Challenge10_H.LEE.gif)
</br>

* The URL of the GitHub repository, with a unique name and a README describing the project </br>
[Repository for this challenge](https://github.com/justinsta624/ORMeCOMBackend)
</br>

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## What to expect for this challenge?

* To build the back end for an e-commerce site by modifying starter code
* To configure a working Express.js API to use Sequelize to interact with a MySQL database
* Your application should use [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect your Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.
* Use the `schema.sql` file in the `db` folder to create your database with MySQL shell commands. Use environment variables to store sensitive data like your MySQL username, password, and database name.
* To provide a link to a walkthrough video that demonstrates its functionality and passes all of the tests. </br>
  [Video Submission Guide](https://coding-boot-camp.github.io/full-stack/computer-literacy/video-submission-guide)
* Your walkthrough video should also shows the application's GET routes to return all -and- single categories, products, and tags being tested in Insomnia.
* Your walkthrough video should also shows the application's POST, PUT, and DELETE routes for categories, products, and tags being tested in Insomnia.

## Associations

To execute association methods on your Sequelize models to create the following relationships between them:
* `Product` belongs to `Category`, and `Category` has many `Product` models, as a category can have multiple products but a product can only belong to one category.
* `Product` belongs to many `Tag` models, and `Tag` belongs to many `Product` models. Allow products to have multiple tags and tags to have many products by using the `ProductTag` through model.
> **Hint:** Make sure you set up foreign key relationships that match the column we created in the respective models.
</br>

## Fill Out the API Routes to Perform RESTful CRUD Operations
Fill out the unfinished routes in `product-routes.js`, `tag-routes.js`, and `category-routes.js` to perform create, read, update, and delete operations using your Sequelize models.
Note that the functionality for creating the many-to-many relationship for products has already been completed for you.
> **Hint**: Be sure to look at the mini-project code for syntax help and use your model's column definitions to figure out what `req.body` will be for POST and PUT routes!
</br>

## Seed the Database
After creating the models and routes, run `npm run seed` to seed data to your database so that you can test your routes.
</br>

## Sync Sequelize to the Database on Server Start
Create the code needed in `server.js` to sync the Sequelize models to the MySQL database on server start.
</br>

## Review

You are required to submit the following for review:
* A walkthrough video demonstrating the functionality of the application.
* The URL of the GitHub repository, with a unique name and a README describing the project.

---






## Review

You are required to submit BOTH of the following for review:

* A walkthrough video demonstrating the functionality of the application and all of the acceptance criteria being met.

* The URL of the GitHub repository. Give the repository a unique name and include a readme describing the project.

---
© 2023 edX Boot Camps LLC. Confidential and Proprietary. All Rights Reserved.




## ⭐ Group 2 Project - Movie Recommendation Application ⭐ 
<a id="top"></a>

[![Bootstrap](https://img.shields.io/badge/CSSFrameworks-Bootstrap-blueviolet)](#Bootstrap)
[![JQuery](https://img.shields.io/badge/JavaScriptUILibrary-JQuery-red)](#JQuery)
[![HTML/CSS](https://img.shields.io/badge/Structure&Style-HTML/CSS-green)](#HTML/CSS)
[![Youtube/OMDb](https://img.shields.io/badge/ServerSideAPIs-Youtube/OMDb-fcba03)](#OMBD)
[![JSON](https://img.shields.io/badge/LocalStorage-JSON-magenta)](#JSON)

# Object-oriented Programming: SVG Logo Maker
![Contributor](https://img.shields.io/badge/Contributor-HanbyeolLee-purple)
[![License](https://img.shields.io/badge/License-MIT-blue)](https://opensource.org/license/MIT)
![GitHub](https://img.shields.io/badge/GitHub-justinsta624-yellow)
![Test](https://img.shields.io/badge/Test-Jest@29.7.0-green)
![Module](https://img.shields.io/badge/Module-FileSystem-magenta)
![Installation](https://img.shields.io/badge/Installation-Inquirer@8.2.4-red)


![image](https://github.com/TeamProjectMovieReview/Team-Project-/assets/143357899/a9e53f48-1584-4cee-baa3-e133a93e56ee)
<br />
<br />
[Live URL of Movie Recommendation Application](https://teamprojectmoviereview.github.io/Team-Project-)
<br />
<br />


<details open>
<summary> Introduction </summary> <br />
  

```
This is our movie trailer platform.

This is where you can be the next potential movie critic and enthusiast.

Our users get to view more movie trailers they can possibly comprehend to find the next perfect movie
for them. Using and integrating Youtube API and ODMP API, you get access from blockbuster films
to hidden gems to movies 20 years old and beyond.

What makes us unique and different from other sources is that you’re not just a viewer but you’re
also a creator. By choosing and saving your favorite movies you get to create a trailer environment
that is just specifically enhanced and handpicked for you.

Easily save your favorite trailers, creating a personalized collection that perfectly reflects your
unique taste. It's a personalized library that you’ve hand chosen to be your own movie sanctuary.

Our platform is more than just watching trailers and discovering your next favorite trailer, its a
community, allowing you to go out into the world and engage with fellow movie enthusiasts and
watch new trailers together.

Allow our website to help you uncover hidden gems and cinematic treasures to find new movies and new
recommendations with the latest data and movies . This is just a beginning, we are constantly
working to improve and enhance user engagement.

It’s like a free show where you can access as many captivating and user engaging trailers
you may possibly desire.
```


</details>

<details open>
<summary> Motivation for development </summary> <br />


```
We created this project because of the increase in the current movie market and to create a user
friendly environment to help individuals to browse trailers and choose specific movies they would prefer.

The rising popularity of streaming services in todays time increases the demand to not only websites
that show movies but also sites that offer specific space to be able to view and discover new movie
trailers that match their taste.

Adding and partnering with movie streamers or potentially starting our own with a subscription would
be a great way to further enhance this project. Movie trailers are also a great way to engage and
captivate user audiences pulling them into their own movie world. Our website and our motivation also
lies in the great diversity within our site.

Allowing discover films they might have otherwise never known existed, or a genre they might like which
they had not thought about. With today’s consumer behavior of preferring bite size and visually
appealing content, our website is ideal as it allows users to watch trailers and decide on their own
weather they’d like to go view this movie.

Another reason for this project is by adding these external API’s, alongside with meeting project
requirements, we’ve been able to integrate high quality content for users and allows them to find exactly
what they are looking for.
```


</details>

<details open>
<summary> User Story </summary> <br />


```
Being the movie enthusiasts that we are, we were aiming to create a website that makes it easier for
us to view and easily navigate through an extensive collection of movies to pick and chose.

We also wanted a way to save possible movies into local storage to be able to revisit them at our
own convenience, for when we obtain a chance to view and watch a movie.This website allows me curated
section for my chosen trailers, allowing me to save and revisit at my own discretion.

It enables me to easily explore endless movies, many unheard of, all while keeping the website engaging.
```
<br />[↑ Back to Top](#top)</br><br />

</details>

<details open>
<summary> Project Requirements </summary> <br />

```
You and your group will use everything you’ve learned over the past six modules to create a real-world
front-end application that you’ll be able to showcase to potential employers.

The user story and acceptance criteria will depend on the project that you create, but your project must
fulfil the following requirements:
```

* Use a CSS framework other than Bootstrap.
* Be deployed to GitHub Pages.
* Be interactive (i.e., accept and respond to user input).
* Use at least two [server-side APIs]
  https://coding-boot-camp.github.io/full-stack/apis/api-resources 
* Does not use alerts, confirms, or prompts (use modals).
* Use client-side storage to store persistent data.
* Be responsive.
* Have a polished UI.
* Have a clean repository that meets quality coding standards
  (file structure, naming, follows class/id naming, indentation, quality comments, etc.).
* Have a quality README (unique name, description, technologies, screenshot, and deployed application).


</details>

<br />
<br />

<details open>
<summary> Presentation of the Project </summary> <br />

Group 2 Presentation of Project: [Movie Recommendation Website]
[https://docs.google.com/presentation/d/10QaO9KH8HtUXj__81ve0SZcpO5DbMbqqQr4iPpbwKks/edit?usp=sharing](https://docs.google.com/presentation/d/1joHsI0JIZWYRWBveIRM8Qj2hoRFw-oNhHvMKiCAOZcM/edit#slide=id.g29f43f0a72_0_15)

to address the following: 
* Elevator pitch: a one minute description of your application
* Concept: What is your user story? What was your motivation for development?
* Process: What were the technologies used? How were tasks and roles broken down and assigned?
  <br /> &ensp; What challenges did you encounter? What were your successes?
* Demo: Show your stuff!
* Directions for Future Development
* Links to the deployed application and the GitHub repository

<br />[↑ Back to Top](#top)</br><br />
</details>
<details open>
<summary> Technologies & Sources used for the project </summary> </br>

<a id="HTML/CSS"></a>
![HTML](https://img.shields.io/badge/Structure-HTML-green)
<br /> &ensp;(1) The structure of the document is defined using HTML5 elements
<br /> &ensp;(2) Iframes: the source pointing to embed YouTube videos for movie trailers.
<br />

![CSS](https://img.shields.io/badge/Style-CSS-green)
<br /> &ensp;(1) Flexbox: to create flexible box layouts for class elements & aside
<br /> &ensp;(2) Flex Direction: to control the direction of the flex container's main axis.
<br /> &ensp;(3) Hover Effects: to add transitions and style changes on hover
<br /> &ensp;(4) Scrollbar Styling: to custom styles applied to scrollbar elements by using:
<br /> &emsp;&emsp;    (a) webkit-scrollbar, webkit-scrollbar-thumb, and webkit-scrollbar-track pseudo-elements.
<br /> &ensp;(5) Transition Effects: applied for smooth animation effects in certain interactions.
<br /> &ensp;(6) Positioning: to use positioning elements, and z-index to control the stacking order of elements.
<br /> &ensp;(7) Cursor Styles: to change the cursor style on buttons.
<br /> &ensp;(8) Object Fit: to control how an image or video should be resized to fit its container.
<br /> &ensp;(9) Opacity: to control the transparency of certain elements.
<br /> &ensp;The Bootstrap framework is included via a CDN link 
<br /> &ensp;https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css
<br /> &ensp;https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css
<br />

<a id="JQuery"></a>
![JQuery](https://img.shields.io/badge/JavaScriptUILibrary-JQuery-red)
<br /> &ensp;(1) The code extensively uses jQuery for DOM manipulation, AJAX requests, and event handling.
<br /> &emsp;&emsp;(a) Promises: used for handling asynchronous operations, such as AJAX requests.
<br /> &emsp;&emsp;(b) Scroll Animation: using jQuery to smoothly scroll to a specific element.
<br /> &emsp;&emsp;(c) Event listeners: to handle various user interactions, such as button clicks/search bar actions.
<br /> &ensp;https://code.jquery.com/jquery-3.4.1.min.js
<br /> &ensp;https://code.jquery.com/jquery-3.6.0.min.js
<br /> &ensp;https://code.jquery.com/jquery-3.7.1.min.js
<br />

<a id="Bootstrap"></a>
![Bootstrap](https://img.shields.io/badge/CSSFrameworks-Bootstrap-blueviolet) 
<br /> &ensp;via a CDN link:
<br /> &ensp;https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js
<br /> &ensp;https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js
<br />

<a id="YOUTUBE"></a>
![APIKEY](https://img.shields.io/badge/ServerSideAPIs-Youtube-fcba03)
<br /> &ensp;The code interacts with the Open Movie Database (OMDb) API to fetch movie data.
<br /> &ensp;https://www.googleapis.com/youtube/v3/search?part=snippet&q=${encodeURIComponent(query)}
<br /> &ensp;https://www.googleapis.com/youtube/v3/videos?id=${videoId}&part=contentDetails&key=${apiKey}
<br /> &ensp;https://www.youtube.com/embed/${videoId}?start=${startTime}&autoplay=1
<br />

<a id="OMBD"></a>
![APIKEY](https://img.shields.io/badge/ServerSideAPIs-OMDb-fcba03)
<br /> &ensp;The code uses the YouTube API to search for movie trailers and fetch details.
<br /> &ensp;https://www.omdbapi.com/?apikey=${omdbApiKey}&s=${searchTerm}
<br /> &ensp;https://www.omdbapi.com/?i=${movie.dataset.id}&apikey=7b82484f
<br /> &ensp;https://omdbapi.com/?s=${searchTerm}&page=1&apikey=7b82484f
<br />

<a id="JSON"></a>
![JSON](https://img.shields.io/badge/LocalStorage-JSON-magenta)
<br /> &ensp;Local Storage.Stringfy: browser's localStorage to store and retrieve favorite movies.
<br />
</details>
<br />


<details open>
<summary> Directions for Future Development </summary> <br />

  
```
An aspect for future development is to add watch history to allow users to be able to find a possible
movie that they may have “lost”. 

This website can also be enhanced by adding additional API’s to fetch live user reviews and ratings 
based on certain movies. We intend to continuously enhance our website possibly creating a mobile
application, so users will be able to watch trailers for potential movies on the go and save for later
preference. 

We can also go ahead and potentially create partnerships so our website is redirected to a possible movie
website such as Netflix or Disney+. Another possibility for future development is to add a downloading
feature to allow users to download their favourite trailers for offline viewing to allow them to access
on possible travels so they know which movie is next on their watch list. 

For other possibilities is adding a real time virtual watch parties to allow users to be able to to watch
and chat in real time. If possible they may be allowed to rate movies in real time. 

If this website is a success we can proceed to add an additional website to present the actual movies
people would like to watch, and possibly adding a cheap user friendly website that allows individuals
to save and present movies to their peers. This would mean an addition of being able to share trailers and
websites on multiple social platform. 

Overall there’s potential for this website to grow in multiple directions that will have to be tackled
one at a time.
