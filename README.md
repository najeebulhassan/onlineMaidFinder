# MERN Online Maid Finder by BC160400406 M Najeeb Ul Hassan

## Description

An Online Maid Finder App built with MERN stack. This App enable three main different flows or implementations:

1. Users browse the different maid services offering from different maids and select the required service according to the hourly rate.
2. Maids Manage their account, once they signup they can add different services to offer in their account which users can see.
3. Admins manage and control the entire App.


* features:
  * Node provides the backend environment for this application
  * Express middleware is used to handle requests, routes
  * Mongoose schemas to model the application data
  * React for displaying UI components
  * Redux to manage application's state
  * Redux Thunk middleware to handle asynchronous redux actions


## Database Seed

* The seed command will create an admin user in the database
* The email and password are passed with the command as arguments
* Like below command, replace brackets with email and password. 
* For more information, see code [here](server/utils/seed.js)

```
npm run seed:db [email-***@****.com] [password-******] // This is just an example.
```

Following are the credentials for 3 different Accounts which are working:

## Admin Account
email: umuhammadnajeeb@gmail.com, password: 12qw!@QW

## Maid Account
email: testmaid@mailinator.com, password: 12qw!@QW

## User Account
email: testclient@mailinator.com, password: 12qw!@QW

## Demo

## How to Run this Application


Required Node Version: 14.17.1
Required npm: 6.14.13

Go into the root folder and run 

- npm install
once node module folder is installed then run 

- npm run dev


If you got some error in the console regarding the IP then kindly share your IP with me so that I can witelist it so that it can communicate
with mongodb atlas. Even though i have whitelist already all the IP's.


There's no need to do anything with .env file I have put all the required key in that already.


