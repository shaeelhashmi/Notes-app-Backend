## Overview:
This app allows users to securely create, update, and delete notes. The authentication system is implemented using Google OAuth2, ensuring a seamless and secure login experience.
## Techstack:
* MongoDB
* Express.
* React
* Node.js
## Features:
* Userauthentication: User authentication using passport.js also google auth API is used so that user can Login using their google account.
* Create Notes: Users can create new notes.
* Update Notes: Users can edit their existing notes.
* Delete Notes: Users can delete notes they no longer need.
* Responsive Design: The app is designed to be responsive and works well on various devices.
## Getting Started:
### Pre-requisites:
* Make sure you have node.js run time envirnment installed in your pc.
* You should have either set up a MongoDB Cloud database or have the MongoDB application installed and running locally.
### Installation:
To run this project locally follow the following steps:
* You can install the zip file of the project from [here](https://github.com/shaeelhashmi/Notes-app-Backend)
* If you have Git installed, type the following command in your terminal:
```
git clone https://github.com/shaeelhashmi/Notes-app-Backend
```
* Then run 
```
cd Notes-app-Backend
```
* Once in the project directory run npm install to download the neccessary packages.
* If you want to access the front-end code you can install the zip file [here](https://github.com/shaeelhashmi/Notes-app-Frontend)
* Or you can install it using git:
```
git clone https://github.com/shaeelhashmi/Notes-app-Frontend
```
### Setting up envirnment:
Create a .env file and add the following things in it:
API_ID="Your google API ID"
API_SECRET="Your google API secret"
CALLBACK_URL="CallBack_URL"
PORT=The port you want to run the application on;
ConnectionPort="Your DB connection string"
Secret="Can be any random pattern of string"
### Execution:
Once all the steps are completed,type the following command in your terminal:
```
Node app.js
```
