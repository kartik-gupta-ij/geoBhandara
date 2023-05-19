<div align="center">
  <h1>🏕️ geoBhandara 🌲</h1>
</div>

<div align="center">
  <h2> https://geobhandara.onrender.com/ </h2>
</div>

<div align="center">
  <h2>- Development Process -</h2>
</div>

## Initial Setup

- [x] Add Landing Page
- [x] Add Bhandaras Page that lists all bhandaras

## Each Bhandara has:

- [x] Name
- [x] Image

## Layout and Basic Styling

- [x] Create our header and footer partials
- [x] Add in Bootstrap

## Creating New Bhandaras

- [x] Setup new bhandara POST route
- [x] Add in body-parser
- [x] Setup route to show form
- [x] Add basic unstyled form

## Style the bhandaras page

- [x] Add a better header/title
- [x] Make bhandaras display in a grid

## Style the Navbar and Form

- [x] Add a navbar to all templates
- [x] Style the new bhandara form

## Add Mongoose

- [x] Install and configure Mongoose
- [x] Setup bhandara model
- [x] Use bhandara model inside of our routes

## Show Page

- [x] Review the RESTful routes we've seen so far
- [x] Add description to our bhandara model
- [x] Show db.collection.drop()
- [x] Add a show route/template

## Refactor Mongoose Code

- [x] Create a models directory
- [x] Use module.exports
- [x] Require everything correctly
    
## Add Seeds File

- [x] Add a seeds.js file
- [x] Run the seeds file every time the server starts

## Add the Comment model

- [x] Make our errors go away
- [x] Display comments on bhandara show page

## Comment New/Create

- [x] Discuss nested routes
- [x] Add the comment new and create routes
- [x] Add the new comment form

## Style Show Page

- [x] Add sidebar to show page
- [x] Display comments nicely

## Finish Styling Show Page

- [x] Add public directory
- [x] Add custom stylesheet

## Auth Pt. 1 - Add User Model

- [x] Install all packages needed for auth
- [x] Define User model

## Auth Pt. 2 - Register

- [x] Cconfigure Passport
- [x] Add register routes
- [x] Add register template

## Auth Pt. 3 - Login

- [x] Add login routes
- [x] Add login template

## Auth Pt. 4 - Logout/Navbar

- [x] Add logout route
- [x] Prevent user from adding a comment if not signed in
- [x] Add links to navbar

## Auth Pt. 5 - Show/Hide Links

- [x] Show/hide auth links in navbar

## Refactor The Routes

- [x] Use Express router to reoragnize all routes

## Users + Comments

- [x] Associate users and comments
- [x] Save author's name to a comment automatically

## Users + Bhandaras

- [x] Prevent an unauthenticated user from creating a bhandara
- [x] Save username + id to newly created bhandara

## Editing Bhandaras

- [x] Add method override
- [x] Add edit route for bhandaras
- [x] Add link to edit page
- [x] Add update route

## Deleting Bhandaras

- [x] Add destroy route
- [x] Add delete button

## Authorization (permission)

- [x] User can only edit his/her bhandaras
- [x] User can only delete his/her bhandaras
- [x] Hide/Show edit and delete buttons

## Editing comments

- [x] Add edit route for comments
- [x] Add edit template
- [x] Add edit button
- [x] Add update route

## Deleting comments

- [x] Add destroy route
- [x] Add delete button

## Authorization part 2: Comments

- [x] User can only edit his/her comments
- [x] User can only delete his/her comments
- [x] Hide/Show edit and delete buttons
- [x] Refactor middleware

## Adding in flash

- [x] Demo working version
- [x] Install and configure connect-flash
- [x] Add bootstrap alerts to header


# Features

- Responsive web design (RWD)
- User authentication (Login/Register/Logout) and authorization (Post/Like/Edit)
- Flash messages responding to users' interaction
- Refactored with ES6 and ES7 syntax (eg: async/await)
- RESTful API

```
-------------------------------------------------------------------------
Normal Routes
-------------------------------------------------------------------------
[Method]  [Route]
GET       /                       Landing page
GET       /login                  Request the user login page
GET       /register               Request the user edit page

-------------------------------------------------------------------------
Users Route
-------------------------------------------------------------------------
[Method]  [Route]
GET       /users                  Fetch all users
POST      /users                  Create new user in database
GET       /users/new              Request the user register page
GET       /users/:id              Show the user information
PATCH     /users/:id              Update user information
DELETE    /users/:id              Delete user information
GET       /users/:id/edit         Request the user edit page

-------------------------------------------------------------------------
Sessions Route
-------------------------------------------------------------------------
[Method]  [Route]
POST      /sessions               Create a session (user login)
GET       /sessions/login         Request the user login page
DELETE    /sessions               Delete a session (user logout)

-------------------------------------------------------------------------
Bhandaras Route
-------------------------------------------------------------------------
[Method]  [Route]
GET       /bhandaras            Fetch all bhandaras
POST      /bhandaras            Create a new bhandara to database
GET       /bhandaras/new        Request the bhandara adding page
GET       /bhandaras/:id        Show the bhandara information
PUT       /bhandaras/:id        Update bhandara information (all)
PATCH     /bhandaras/:id        Update bhandara information (part)
DELETE    /bhandaras/:id        Delete a bhandara
GET       /bhandaras/:id/edit   Request the bhandara editing page
POST      /bhandaras/:id/likes  Like the bhandara

-------------------------------------------------------------------------
Comments Route
-------------------------------------------------------------------------
[Method]  [Route]
POST      /bhandaras/:id/comments       Create a new comment
PATCH     /bhandaras/:id/comments/:cid  Update comment
DELETE    /bhandaras/:id/comments/:cid  Delete comment
```

# Technologies

## Frontend

- [Bootstrap](https://getbootstrap.com/)
- [ejs](https://ejs.co/)

## Backend

- [express](https://gulpjs.com/)
- [mongodb](https://webpack.js.org/concepts/)

Check [`package.json`](https://github.com/kartik-gupta-ij/geoBhandara7267/blob/master/package.json) file for more information.

# Getting Started

Follow the instructions below to set up the environment and run this project on your local machine.

1. Clone this repository.

```bash
# Clone repository
$ git clone https://github.com/kartik-gupta-ij/geoBhandara.git
```

2. Install dependencies via NPM or Yarn

```bash
# Install dependencies via npm
$ npm install

# Install dependencies via yarn
$ yarn install
```

3. Run the server with [nodemon](https://nodemon.io/) and open a browser to visit [http://localhost:3000/](http://localhost:3000/).

```bash
# Run server
$ npm start
```






# geoBhandara PH
A Filipino version of geoBhandara ~ from The Web Developer Bootcamp 2021 by Colt Steele: https://www.udemy.com/course/the-web-developer-bootcamp/ 


Deployed on Heroku:
https://geoBhandara7267.herokuapp.com/


Stack:
Node JS, Express JS, MongoDB, Mongoose, EJS


<h2>Gallery</h2>


Home

![image](https://user-images.githubusercontent.com/73538719/114265389-21691600-9a23-11eb-8841-568a46e16284.png)


The Map

![image](https://user-images.githubusercontent.com/73538719/114261441-2ae78380-9a0d-11eb-9b2d-1c69cccd7290.png)


Search

![image](https://user-images.githubusercontent.com/73538719/114261593-f627fc00-9a0d-11eb-950a-36ca1d87269a.png)


Pagination

![image](https://user-images.githubusercontent.com/73538719/114261851-697e3d80-9a0f-11eb-851f-59af7e5ccfef.png)


Show Page

![image](https://user-images.githubusercontent.com/73538719/114261923-a5190780-9a0f-11eb-864a-dca32ab085a6.png)


Leaving a Review

![image](https://user-images.githubusercontent.com/73538719/114261965-dbef1d80-9a0f-11eb-92ba-a8a1b0a91bfc.png)


Bhandaras by Current User

![Screenshot from 2021-04-10 15-20-22](https://user-images.githubusercontent.com/73538719/114262465-a566d200-9a12-11eb-866a-e1790a064c84.png)


Adding a New Bhandara

![image](https://user-images.githubusercontent.com/73538719/114262124-d514da80-9a10-11eb-8f39-00779dc5c6ed.png)


Editing a Bhandara

![image](https://user-images.githubusercontent.com/73538719/114262218-4bb1d800-9a11-11eb-8ac6-0133a60bf6d8.png)
![image](https://user-images.githubusercontent.com/73538719/114262284-b6fbaa00-9a11-11eb-8e10-fefbfcbf46ae.png)
