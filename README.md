# YelpCamp

![image](https://github.com/vinodkhichar/YelpCamp/assets/95199749/b8b379e3-3917-4cd1-9fac-60b9614be4f6)
![image](https://github.com/vinodkhichar/YelpCamp/assets/95199749/26830c43-6042-449c-9402-4e7efb45aef7)
![image](https://github.com/vinodkhichar/YelpCamp/assets/95199749/4d6e6fce-a269-4882-abf4-34b053a36f62)

## Features

- **User Authentication:** Sign up and log in securely to YelpCamp using a personalized user account.
- **Campground Listings:** Browse through a diverse range of camping sites, each with detailed descriptions, photos, and user reviews.
- **Campground Reviews:** Share your camping experiences by leaving reviews and ratings for campgrounds you've visited.
- **Interactive Map:** Explore campgrounds on an interactive map to help plan your next outdoor getaway.
- **Responsive Design:** Enjoy a seamless experience on various devices, from desktop to mobile.

## Technologies Used
- **Node.js**
- **Express.js**
- **MongoDB**
- **Passport.js (for authentication)**
- **Mapbox API (for maps)**
- **EJS (Embedded JavaScript) for views**
- **Bootstrap (for styling)**

## Installation

1. Create a cloudinary account to get an API key and secret code
    ```plaintext
    git clone `https://github.com/vinodkhichar/YelpCamp.git`
    cd yelpcamp
    npm install
3. Create a `.env` file in the root directory with the following variables:

   ```plaintext
   DATABASEURL='<url>'
   API_KEY=''<key>
   API_SECRET='<secret>'
4. Run `mongod` in another terminal and `node app.js` in the terminal with the project.
   Then go to localhost:3000.
