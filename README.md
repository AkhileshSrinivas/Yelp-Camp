# Yelp-Camp

![alt text](https://res.cloudinary.com/web-dev-app/image/upload/v1619012118/YelpCamp/Screenshot_503_ujwps3.png)

![alt text](https://res.cloudinary.com/web-dev-app/image/upload/v1619012821/YelpCamp/Screenshot_513_nfoaos.png)

![alt text](https://res.cloudinary.com/web-dev-app/image/upload/v1619013505/YelpCamp/Screenshot_514_f0xvmq.png)

YelpCamp is a website where users can create and review campgrounds. In order to review or create a campground, you must have an account.

This project was created using Node.js, Express, MongoDB, and Bootstrap. Passport.js was used to handle authentication.

# Live Demo

The app is deployed on Heroku and available to use -
[YelpCamp](https://akhilesh-yelpcamp.herokuapp.com/)

# Features

- Authentication:

  - User login with username and password
  - Admin sign-up with admin code

- Authorization:

  - One cannot manage posts and view user profile without being authenticated
  - One cannot edit or delete posts and comments created by other users
  - Admin can manage all posts and comments

- Manage campground posts with basic functionalities:

  - Create, edit and delete posts and comments
  - Upload campground photos
  - Display campground location on Map
  - Search existing campgrounds using Map

- Manage user account with basic functionalities:

  - Profile page setup with sign-up

- Flash messages responding to users' interaction with the app

- Responsive web design

# Custom Enhancements

- Update campground photos when editing campgrounds
- Update personal information on profile page
- Improve image load time on the landing page using Cloudinary
- Use Helmet to strengthen security

# Getting Started

This app contains API secrets and passwords that have been hidden deliberately, so the app cannot be run with its features on your local machine. However, feel free to clone this repository if necessary.

# Built with

# Front-end

- [ejs](https://ejs.co/)
- [mapbox APIs](https://docs.mapbox.com/)
- [Bootstrap](https://getbootstrap.com/docs/3.3/)

# Back-end

- [express](https://expressjs.com/)
- [mongoDB](https://www.mongodb.com/)
- [mongoose](https://mongoosejs.com/)
- [async](http://caolan.github.io/async/v3/)
- [crypto](https://nodejs.org/api/crypto.html#crypto_crypto)
- [helmet](https://helmetjs.github.io/)
- [passport](http://www.passportjs.org/)
- [passport-local](https://github.com/jaredhanson/passport-local#passport-local)
- [express-session](https://github.com/expressjs/session#express-session)
- [method-override](https://github.com/expressjs/method-override#method-override)
- [cloudinary](https://cloudinary.com/)
- [geocoder](https://github.com/wyattdanger/geocoder#geocoder)
- [connect-flash](https://github.com/jaredhanson/connect-flash#connect-flash)

# Platforms

- [Cloudinary](https://cloudinary.com/)
- [Heroku](https://dashboard.heroku.com)
