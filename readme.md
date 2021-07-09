# YelpCamp

![image](https://user-images.githubusercontent.com/63163693/124935413-44579600-e023-11eb-917c-7fbede842744.png)

![image](https://user-images.githubusercontent.com/63163693/124935513-589b9300-e023-11eb-90f9-57f88b0a3871.png)

YelpCamp is a website where users can create and review campgrounds. In order to review or create a campground, you must have an account. This project was part of Colt Steele's web dev course on udemy.

This project was created using Node.js, Express, MongoDB, and Bootstrap. Passport.js was used to handle authentication.

## Features:
1. Users can create, edit, and remove campgrounds
2. Users can review campgrounds once, and edit or remove their review
3. User profiles include more information on the user (full name, email, phone, join date), their campgrounds, and the option to edit their profile or delete their account
4. Search campground by name or location
5. Sort campgrounds by highest rating, most reviewed, lowest price, or highest price
6. Trying to add weather forecasting for next 10 days


## Custom Enhancements:
-- Update campground photos when editing campgrounds

-- Update personal information on profile page

-- Improve image load time on the landing page using Cloudinary

-- Use Helmet to strengthen security

## Build and Run

### Prerequisites -

1. Install Node.Js and npm
   - Refer [here](https://nodejs.org/en/download/)
2. Database account
   - Refer [here](https://www.mongodb.com/cloud)

### Run Software

1. Clone Repo
   - `$> git clone https://github.com/kkthaker/YelCamp_CampaignWebsite.git
2. Change Directory
   - `$> cd YelpCamp/`
3. Install Dependencies
   - `$> npm install`
4. Environement Variables - cmd line setup
   - `$env:PORT = "3000"`
   - `$env:DATABASEURL = "your_databse_url_generated_from_mongo_cloud"`
5. Start server
   - `$> node app.js`

Go to http://localhost:3000/
