# Overview

With over 12 million e-commerce sites worldwide, a significant portion of the web is focused on selling and buying goods. As a software engineer my goal is to improve  user shopping experience through improved UI, and to improve development time while decreasing maitenance through building dynamic applications.

This web app is representative of a boutique e-commerce site, however it is a better reflection of a content management site. The base of the site is in place and all the boutique shop owner would need to do is to manage the inputs of their product; the CSS will scale to accommodate unlimited products.

For this project the frontend views share a directory with the backend build. To view the project in a local environment, use command 'npm start' to spin up an Express server on Port 5000. To view the pages, navigate to URL "http://localhost:5000/" that will deliver the root index.html view.

**At time of commit, project is in prep stages to be deployed on Heroku Cloud Platform**

The two main purposes for writing this application: 
·E-commerce is a MAJOR player in modern websites, it's important to know how best to serve those companies and clients that focus on it.
·An e-commerce site, when broken down, has all of the components that just about any site would ever need to have: ability to add and showcase product, register and account, login a user, make lists of items (cart), persist data for when a user returns to the site.  


{Provide a link to your YouTube demonstration.  It should be a 4-5 minute demo of the software running (starting the server and navigating through the web pages) and a walkthrough of the code.}

[Software Demo Video](https://youtu.be/NFoY3HWj7eE)

# Web Pages

{Describe each of the web pages you created and how the web app transitions between each of them.  Also describe what is dynamically created on each page.}

The first page that is created is a home page, with a nav bar at the top. The contenthas been modularized and is being dynamically injected via EJS. This is important for scale and maintainability purposes, because if changes needed to be made to something such as the < navigation > it would only need to be changed in one location, making large sites and projects much easier to maintain. 

Once there, the user can navigate to the Product page, which shows detailed product descriptions, or they can Login. 

If a user logs in, their user data is authenticated and then they would have admin access to add new product items. On the admin/add product screen they would find a form to fill out, and submit which would add a product to the database and then would populate to the product page to be displayed. 



# Development Environment
IDE—
 Microsoft Visual Studio Code

Stack—
MongoDb- noSQL database
Express
Node.js

Dependencies—
Mongoose- Object Data Modeling library to manage relationship between data and ojects in code to db
Csurf & express-session to set a CSRF token
Bcrypt to hash passwords
EJS, Embedded JavaScript Templating- to dynamically populate html
Dotenv- stores secret environment variables


# Useful Websites

* [Medium- Node.js](https://levelup.gitconnected.com/render-dynamic-content-in-nodejs-using-templates-a58cae681148)

* [Dynamic Express + EJS](https://ncoughlin.com/posts/express-ejs-render-page-dynamic-content/)

# Future Work

* Use React to build frontend
* Seperate backend from frontend, deploy backedn as API, then use fetch or Axios to make data request.
* Add additional features and function: search/filter options, product detail options (quantity, size, cart add, favorite list, etc)
