# Trouvaille Campground Website

Trouvaille is a website where users can create and review campgrounds. In order to review or create a campground, you must have an account. This project was part of Colt Steele's web dev course on udemy.  

This project was created using Node.js, Express, MongoDB, and Bootstrap. Passport.js was used to handle authentication.  

## Features
* Users can create, edit, and remove campgrounds
* Users can create, and remove comment on campground
* Users can review campgrounds once, and edit or remove their review


## Run it locally
1. Install [mongodb](https://www.mongodb.com/)
2. Create a cloudinary account to get an API key and secret code

```
git clone https://github.com/adiyamhaske/Campground-Website
cd yelpcamp
npm install
```

Create a .env file (or just export manually in the terminal) in the root of the project and add the following:  

```
DATABASEURL='<url>'
API_KEY=''<key>
API_SECRET='<secret>'
```

Run ```mongod``` in another terminal and ```node app.js``` in the terminal with the project.  

Then go to [localhost:3000](http://localhost:3000/).

To get google maps working check [this](https://github.com/nax3t/google-maps-api) out.

## Upload Site to Heroku
```
git config --global user.email "abc@email.com"
git init
git add.
git commit -m "Add_your_Comment"

heroku login  -i {add your mail and password}
heroku create
git push heroku master
```

## Google Maps Tutorial

See video tutorial [here](https://www.youtube.com/watch?v=B4OuCjQLJ9k)

See slides [here](http://slides.com/nax3t/yelpcamp-refactor-google-maps)
