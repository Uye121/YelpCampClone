
# YelpCamp

**YelpCamp** is a Node.js web application with RESTful routing from the Udemy course [The Web Developer Bootcamp](https://www.udemy.com/the-web-developer-bootcamp/).

## Live Demo
To see the app in action, go to [https://yelp-camp-0819.herokuapp.com/](https://yelp-camp-0819.herokuapp.com/).

## Features
* Authentication:
  
  * User login with username and password

* Authorization:

  * Authentication is required to manage posts

  * User can only edit or delete their own posts and comments

* Campground functionalities:

  * Create, edit and delete posts and comments

  * Upload and edit campground photos

  * Add and edit campground pricing

  * Display campground location on Google Map

* Misc:

  * Flash messages for user's successful or failed interaction

  * Responsive web design

## Built With

### Front-end
* [Bootstrap 3](https://getbootstrap.com/docs/3.3/)
* [ejs](https://ejs.co/)
* [Google Map API](https://cloud.google.com/maps-platform/)

### Back-end

* [body-parser](https://www.npmjs.com/package/body-parser)
* [cloudinary](https://cloudinary.com/)
* [connect-flash](https://github.com/jaredhanson/connect-flash#connect-flash)
* [dotenv](https://www.npmjs.com/package/dotenv)
* [express](https://expressjs.com/)
* [method-override](https://github.com/expressjs/method-override#method-override)
* [moment](https://momentjs.com/)
* [mongoDB](https://www.mongodb.com/)
* [mongoose](http://mongoosejs.com/)
* [multer](https://www.npmjs.com/package/multer)
* [passport](http://www.passportjs.org/)
* [passport-local](https://github.com/jaredhanson/passport-local#passport-local)
* [passport-local-mongoose](https://www.npmjs.com/package/passport-local-mongoose)

## Deployment

* [Heroku](https://www.heroku.com/)