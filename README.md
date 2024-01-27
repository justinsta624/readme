<a ID="readme-top"></a>

<div align="center">
  
# Gamersheim: Interactive Full-Stack Project

[![Node.js Badge](https://img.shields.io/badge/Node.js-393?style=for-the-badge&logo=nodedotjs&logoColor=fff)](https://nodejs.org/en)
[![MySQL2 Badge](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![Express Badge](https://img.shields.io/badge/Express-000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![Bcrypt Badge](https://img.shields.io/badge/Bcrypt-338?style=for-the-badge&logo=javascript&logoColor=white)](https://www.npmjs.com/package/bcrypt)
[![Dotenv Badge](https://img.shields.io/badge/Dotenv-000?style=for-the-badge&logo=javascript&logoColor=white)](https://www.npmjs.com/package/dotenv)
[![Sequelize Badge](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)](https://www.npmjs.com/package/sequelize)
[![Handlebar Badge](https://img.shields.io/badge/Handlebars%20js-f0772b?style=for-the-badge&logo=handlebarsdotjs&logoColor=black)](https://www.npmjs.com/package/handlebars)

</div>
</div>


## Goal of the Project

* Empowering Gaming Enthusiasts: Provide an immersive full-stack game platform for gaming enthusiasts to effortlessly discover, play, and organize their favorite games.
* Showcasing Seamless User Experience: Demonstrate the project's commitment to an intuitive user interface, ensuring easy navigation, enhanced usability, and responsiveness across various devices and screen sizes.
* Highlighting Rich Game Collection: Serve as a focal point in the portfolio by offering an extensive game collection categorized by genres. Include relevant information such as genre, release date, and brief descriptions for effortless exploration.
* Integrating External APIs for Enriched Experience: Seamlessly fetch and display game details using integrated APIs for trailers, screenshots, and reviews. Enhance the gaming experience by integrating with external platforms.
* Engaging Users with Interactive Features: Provide an interactive experience with game trailers, featuring auto play, full-screen mode, and options to comment or share trailers.
* Enhancing Search and Recommendation System: Design a search box with autocomplete functionality. Incorporate a drop-down box with suggested games based on user preferences and trends.
* Enabling Personalization with Favorite Games: Allow users to create and manage a personalized list of favorite games. Implement local storage for saving and retrieving user-selected favorites.
* Ensuring Secure User Authentication: Implement a secure user authentication system with encrypted passwords. Enable users to create accounts, log in, and manage profiles securely.
* Facilitating Social Engagement: Enable social media sharing options for game-related activities and achievements.
* Implementing Feedback and Rating System: Create a user feedback and rating system for games, displaying average ratings and reviews to assist users in making informed decisions.
* Cultivating Multiplayer Engagement: Incorporate features for multiplayer engagement, including connecting with friends, joining gaming communities, and participating in multiplayer games.
* Promptly Notifying Users of Updates and Events: Implement a notification system for new game releases, updates, and events.
* Building a Robust Backend for Performance: Develop a robust backend system efficiently handling user requests, updating the game database, and ensuring overall platform performance and scalability.
  
</div>
</div>


## Table of Contents

- [Goal of the Project](#Goal-of-the-Project)
- [Description](#Description)
- [User Story](#User-Story)
- [Acceptance Criteria](#Acceptance-Criteria)
- [How to Use](#how-to-use)
- [Technology Used](#technology-used)
- [License](#license)
- [References](#references)
- [Walkthrough Video](#Walkthrough-Video)
- [Collaborators](#Collaborators)

## User Story

```
As a gaming enthusiast, I want to access an interactive full-stack game platform that provides a
seamless and engaging experience, allowing me to discover, play, and organize my favorite games
effortlessly.
```

## Acceptance Criteria

```
WHEN a user accesses the game platform
THEN they should experience an intuitive user interface with easy navigation, enhancing overall
usability and responsiveness on various devices and screen sizes.

WHEN a user explores the game collection
THEN they should find an extensive array of games categorized by genres, including relevant
information like genre, release date, and a brief description for effortless exploration.

WHEN a user views game details
THEN the platform should seamlessly fetch and display information using integrated APIs for
trailers, screenshots, and reviews, ensuring a rich gaming experience across external platforms.

WHEN a user engages with game trailers
THEN they should have an interactive experience with features such as auto play, full-screen mode,
and options to comment or share trailers.

WHEN a user searches for games
THEN the platform should provide autocomplete functionality and offer game recommendations as users
type, incorporating a drop-down box with suggestions based on preferences and trends.

WHEN a user manages favorite games
THEN they should have the ability to create a personalized list, with local storage implemented to
save and retrieve their favorite games for future reference.

WHEN a user interacts with user authentication
THEN the system should securely allow account creation, login, and profile management with encrypted
passwords and secure storage of user information.

WHEN a user wants to share achievements
THEN the platform should enable social media sharing options for favorite games on various platforms.

WHEN a user provides feedback
THEN the platform should facilitate a user feedback and rating system for games, displaying average
ratings and reviews to assist users in making informed decisions.

WHEN a user desires multiplayer engagement
THEN the platform should incorporate features to connect with friends, join gaming communities, and
participate in multiplayer games.

WHEN there are updates or events related to favorite games
THEN the platform should implement a notification system to inform users promptly.

WHEN a user interacts with the backend
THEN the platform should have a robust backend system efficiently handling user requests, updating
the game database, and ensuring overall performance.
```

## How to Use

### Installation

GAMERSHEIM is deployed VIA Heroku (Utilising JawsDB as Database-as-a-service)
Installation is not required if accessing VIA the below link:

<a href="https://polar-journey-77005-c598f31c0871.herokuapp.com/"> GAMERSHEIM(Heroku) </a>

If you would like to Clone -or- Fork the repository to contribute then folow the below steps.

1. Clone -or- Fork the repository
2. Run the below in console install necessary packages

```
npm i
```
3. After NPM packages have been installed, you'll need to set up your MySQL database for the application to read and write to. Log into MySQL2:
```
mysql -u root -p
```
4. Within mysql2 - create the datbase with the schema provided, run the below command in the root folder (the below is the relative path):
```
source ./db/schema.sql
```
5. Exit MySQL2:
```
quit
```
6. Seeding -or- populating a database with necessary data
```
npm run seed
```
7. You can run start the server once packages have been installed and the database is created. Run the below in the CLI:
```
node server.js
```

### Usage

`Intuitive User Interface` Create a user-friendly interface for seamless navigation.
Ensure responsiveness across various devices and screen sizes. </div> 

`Diverse Game Collection` Curate an extensive game collection categorized by genres.
Display relevant information such as genre, release date, and brief descriptions. </div> 

`Integration of Game APIs` Implement APIs to fetch and display game details, including trailers and reviews.
Integrate with external platforms for an enriched gaming experience. </div> 

`Interactive Game Trailers` Develop an interactive section for game trailers with auto-play and full-screen options.
Include features for user comments and sharing of trailers. </div> 

`Search and Recommendation System` Design a search box with autocomplete functionality.
Integrate a drop-down box with suggested games based on user preferences and trends. </div> 

`Favorite Games Section` Enable users to create and manage a personalized list of favorite games.
Implement local storage for saving and retrieving user-selected favorites. </div>

`User Authentication` Implement a secure user authentication system with encrypted passwords.
Allow users to create accounts, log in, and manage profiles securely. </div> 

`Social Integration` Enable social media sharing options for game-related activities and achievements. </div> 

`Feedback and Rating System` Create a user feedback and rating system for games.
Display average ratings and reviews to assist users in decision-making. </div> 

`Multiplayer Functionality` Incorporate features for multiplayer engagement, including connecting with friends and joining gaming communities. </div> 

`Notifications and Updates` Implement a notification system for new game releases, updates, and events. </div> 

`Responsive Backend` Develop a robust backend system for efficient user request handling and database management.
Ensure overall platform performance and scalability. </div> 


## Technology-Used

- **Node.js**: Runtime environment for executing server-side JavaScript code.
- **Express**: Web application framework for building RESTful APIs.
- **Express-Handlebars**: Template engine for rendering HTML templates.
- **Express-Session**: Middleware for managing user sessions.
- **MySQL2**: MySQL database driver for Node.js.
- **Sequelize**: Promise-based ORM for interacting with databases.
- **Bcrypt**: Library for securely hashing passwords.
- **Dotenv**: Utility for loading environment variables.
- **JawsDB**: Providing managed MySQL databases, ideal for scalable web applications.
- **Heroku**: A cloud platform that offers easy deployment and management of web applications.

## License

For details click on the following link to go to the "LICENSE" file:

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge&logo=mit)](https://opensource.org/licenses/MIT)


## References



### Screenshots

<div align="center">
  
![#1.Screenshot of the Gamersheim Homepage](./assets/images/FIFA_23_Cover.jpg)

![#2.Screenshot of the Popular Category](./assets/images/Devil_May_Cry_5.jpg)

![#3.Screenshot of the Upcoming Category](./assets/images/Doom_cover_art.jpg)

![#4.Screenshot of the Platforms Category](./assets/images/Grand_Theft_Auto_V.png)

![#5.Screenshot of the Genre Category](./assets/images/Resident_Evil_3.jpg)

![#6.Screenshot of the User Category](./public/images/Witcher_3_cover_art.jpg)

</div>
</div>


## Collaborators
[![OzdalDogru](https://img.shields.io/badge/Ozdal-Dogru-blueviolet)](https://github.com/ozdaldogru)
[![AllanYuen](https://img.shields.io/badge/Allan-Yuen-red)](https://github.com/AllanYuen)
[![MatthewBeaubien](https://img.shields.io/badge/Matthew-Beaubien-green)](https://github.com/Matthew-Beaubien)
[![CharlotteMarchildon](https://img.shields.io/badge/Charlotte-Marchildon-fcba03)](https://github.com/charlottemarchildon)
[![JustinLee](https://img.shields.io/badge/Justin-Lee-magenta)](https://github.com/justinsta624)


## Deployment

Github direct link:
https://github.com/ozdaldogru/Gamersheim-Interactive-Full-Stack-Project- 


Github HTTPS Clone link:



Github Deployment link:


Heroku Deployment link:

---

## Description

Huber's Tech Blog is a website that allows users to publish blog posts and posts comments against blogs to generate discussion.

High level features of the forum are:

* User management (logging in, account creation)
* Ability for user to post blogs about topics of interest
* Ability for users to comment on blogs

This application is designed following the MVC paradigm without a base code.

## Table of contents

- [User Story](#user-story)
- [User Acceptance Critiera](#user-acceptance-criteria)
- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [License](#license)
- [Contributing](#contributing)
- [Testing](#testing)
- [Technologies Used](#technologies-used)
- [Questions](#questions)

## User Story <a ID="user-story"></a>

This forum was developed with this user story in mind:

```
AS A developer who writes about tech

I WANT a CMS-style blog site
SO THAT I can publish articles, blog posts, and my thoughts and opinions
```
<p align="right">(<a href="#readme-top">back to top</a>)</p>

## User Acceptance Criteria <a ID="user-acceptance-criteria"></a>

### This server was developed with the below User acceptance criteria:

```
GIVEN a CMS-style blog site

WHEN I visit the site for the first time
THEN I am presented with the homepage, which includes existing blog posts if any have been posted; navigation links for the homepage and the dashboard; and the option to log in

WHEN I click on the homepage option
THEN I am taken to the homepage

WHEN I click on any other links in the navigation
THEN I am prompted to either sign up or sign in

WHEN I choose to sign up
THEN I am prompted to create a username and password

WHEN I click on the sign-up button
THEN my user credentials are saved and I am logged into the site

WHEN I revisit the site at a later time and choose to sign in
THEN I am prompted to enter my username and password

WHEN I am signed in to the site
THEN I see navigation links for the homepage, the dashboard, and the option to log out

WHEN I click on the homepage option in the navigation
THEN I am taken to the homepage and presented with existing blog posts that include the post title and the date created

WHEN I click on an existing blog post
THEN I am presented with the post title, contents, post creator’s username, and date created for that post and have the option to leave a comment

WHEN I enter a comment and click on the submit button while signed in
THEN the comment is saved and the post is updated to display the comment, the comment creator’s username, and the date created

WHEN I click on the dashboard option in the navigation
THEN I am taken to the dashboard and presented with any blog posts I have already created and the option to add a new blog post

WHEN I click on the button to add a new blog post
THEN I am prompted to enter both a title and contents for my blog post

WHEN I click on the button to create a new blog post
THEN the title and contents of my post are saved and I am taken back to an updated dashboard with my new blog post

WHEN I click on one of my existing posts in the dashboard
THEN I am able to delete or update my post and taken back to an updated dashboard

WHEN I click on the logout option in the navigation
THEN I am signed out of the site

WHEN I am idle on the site for more than a set time
THEN I am able to view posts and comments but I am prompted to log in again before I can add, update, or delete posts

```

### Additional requirements:

* Application folder structure must follow Model-View-Conrtoller (MVC) paradigm
* Use of the following technologies
    * Express-handlebars
    * MySQL2
    * Sequelize
    * Express.js API for controllers
    * Manage environment variables via dotenv package
    * bcrypt package to has passwords
    * Express-session
    * Connect-session-sequelize

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Screenshots <a ID = "video-screenshots"></a>

### Screenshots

Screenshot of the Homepage listing all Blogs 
<div align="center">

![Screenshot of the Homepage listing all Blogs ](./public/images/screenshot1.png)
</div>

Screenshot of response the User Dashboard to add, edit, delete their blogs
<div align="center">

![Screenshot of the response to GET all products](./public/images/screenshot2.png)
</div>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Installation

Huber's Tech Blog is deployed via Heroku (Utilising JawsDB as Database-as-a-service)
Installation is not required if accessing via the below link:

<a href="https://huber-tech-blog-ed7fd58460b2.herokuapp.com/"> Huner's Tech Blog (Heroku)" </a>

If you would like to Clonse or fork the repository to contribute then folow the below steps.

1. Clone or fork the repository
2. Run the below in console install necessary packages

```
npm i
```
3. After NPM packages have been installed, you'll need to set up your MySQL database for the application to read and write to. Log into MySQL2:
```
mysql -u root -p
```
4. Within mysql2 - create the datbase with the schema provided, run the below command in the root folder (the below is the relative path):
```
source ./db/schema.sql
```
5. Exit MySQL2:
```
quit
```
6. Optional - you can seed some data into the database while you are in mysql2 (Skip this step if you are going to use real data)
```
source ./seeds/seed.sql
```
7. You can run start the server once packages have been installed and the database is created. Run the below in the CLI:
```
node server.js
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

* Access the home page of the Techblog to begin.
* The website allows users view only access to read blogs and comments.
* On the home page, clicking on a blog's title will open up the blog to show comments
* Comments can only be added once the user has signed in
* There is the option to sign up or log in and existing account to enable more features on the website
* Once signed in, a user can add comments against blogs
* The user will also have access to their dashboard which lists all blogs written by them.
* The user has the ability to add more blogs, edit exiting blogs or delete their blogs
* The website is configured so that sessions last 5 minutes (you will be logged out after this time elapses and will require logging in again)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

This application can be used in conjunction with licensing covered in  <b>MIT Lcensee</b>

(Click on the badge for details of the license)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

To contribute to this application, please reach out to me via my contact details below

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Testing

Automated Test scripts have not been developed for this application



<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Technologies used <a ID="technologies-used"></a>

- **Node.js**: Runtime environment for executing server-side JavaScript code.
- **Express**: Web application framework for building RESTful APIs.
- **Express-Handlebars**: Template engine for rendering HTML templates.
- **Express-Session**: Middleware for managing user sessions.
- **MySQL2**: MySQL database driver for Node.js.
- **Sequelize**: Promise-based ORM for interacting with databases.
- **Bcrypt**: Library for securely hashing passwords.
- **Dotenv**: Utility for loading environment variables.
- **Tailwind CSS**: Utility-first CSS framework for styling the application's frontend.
- **JawsDB**: Providing managed MySQL databases, ideal for scalable web applications.
- **Heroku**: A cloud platform that offers easy deployment and management of web applications.

**Development Tools**:

- **Nodemon**: Development tool for auto-reloading the server during development.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Questions

- Visit my GitHub page: <a href="https://github.com/hybee234"> hybee234 </a>
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>

# ⭐ Object-Relational Mapping: E-Commerce BackEnd ⭐
    
![Contributor](https://img.shields.io/badge/Contributor-Hanbyeol(Justin)Lee-purple)
[![License](https://img.shields.io/badge/License-MIT-blue)](https://opensource.org/license/MIT)
![ORMLibrary](https://img.shields.io/badge/ORMLibrary-Sequelize-yellow)
![DataBase](https://img.shields.io/badge/DataBase-MySql2-green)
![Security](https://img.shields.io/badge/Security-Dotenv-magenta)
![RouteApplication](https://img.shields.io/badge/RouteApplication-Express.js-red)

## Outcome

Followings are the outcomes of the challenge 13:

* A walkthrough video demonstrating the functionality of the application </br>
[Walk-Through Video: Webm file](https://drive.google.com/file/d/1DesRcjh71bOVOYdFWXmtrp2ilY5Ni-Oo/view) </br>
[Walk-Through Video: GIF file](https://github.com/justinsta624/MeetyourSVGMaker/blob/main/outcome/231210_Walk-Through-Video_Challenge10_H.LEE.gif)

* The URL of the GitHub repository, with a unique name and a README describing the project </br>
[Repository for this challenge](https://github.com/justinsta624/ORMeCOMBackend)

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

## Fill Out the API Routes to Perform RESTful CRUD Operations
Fill out the unfinished routes in `product-routes.js`, `tag-routes.js`, and `category-routes.js` to perform create, read, update, and delete operations using your Sequelize models.
Note that the functionality for creating the many-to-many relationship for products has already been completed for you.
> **Hint**: Be sure to look at the mini-project code for syntax help and use your model's column definitions to figure out what `req.body` will be for POST and PUT routes!

## Seed the Database
After creating the models/routes, run `npm run seed` to seed data to your database so that you can test your routes.
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
