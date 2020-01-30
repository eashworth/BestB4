# BestB4

                  (
                   )
              __..---..__
          ,-='  /  |  \  `=-.,
          :--..___________..--;
           \.,_____________,./


### BestB4 Video
Watch a video demonstration of the app [here](https://www.youtube.com/watch?v=swMdISwc3yc&feature=youtu.be)!

### Front End Repository

The front end repository for this project is available at: <br>
https://github.com/eashworth/bestB4-Front-End <br>

### Project Description

A final project by Eithel, Elsie, Jules, Mackenzie and Valeria.  BestB4 is a website to helps the world waste less food by allowing people to easily give away food they wont use to other people in their local community.

As well as allowing users to list their own food to give away and find available in their local area there is also a link to Google Maps so people know exactly where to go to pick up their free food.  There's even recipe sugestions based on the ingredients based in your local area.

### Motivation

1.3 billion tones of food gets lost or wasted every year we wanted to help reduce that.

### Homepage

![Alt text](/Images/Homepage.png?raw=true "Home Page")

### Tech Stack

Mongo <br>
Express <br>
React <br>
Node <br>
Cypress <br>
Jest <br>
Insomnia (https://insomnia.rest/) <br>
Java Script <br>
Google API <br>
Spoonacular API <br>
Redux <br>
Balsimiq <br>
Trello <br>


### Features

List food to give away.
Delete food from your inventory when you have given it away or it has passed it's expiry date. <br>
Find food in your local area that people are giving away. <br>
Contact a user who is listing food you want. <br>
Get directions collect food via a Google API. <br>
Get recipe sugestions based on what ingredients are available in your local area vis a Spoonacular API <br>


### Installation

```bash
npm install
```

### Tests

#### How to run front end feature tests

1. Run back end server (from backend directory) <br>

$ BestB4 <br>

```
node server.js

```
2. Run front end server (from front end directory) <br>

$ client <br>

```
npm run start

```

3. Run Cypress (from front end directory)

$ Client

```
node_modules/.bin/cypress open
```

The Cypress UI will then open automatically and you will see a list of feature tests that can be run.

### How to use

To run back end repository.
```bash
node server.js
```

To run front end repository
```
npm run start
```

You can now view in your browser of choice by visiting:

http://localhost:3000/

#### User Stories

As a user <br>
So I can find unwanted food <br>
I can view a list of available food <br>

As a user <br>
So I can access my account <br>
I can log in <br>

As a user <br>
So I can create an account <br>
I can sign up <br>

As a user <br>
So I can give away food I won't use <br>
I can list a food item <br>

As a user <br>
So people can see who I am <br>
I can add my gravatar profile picture <br>

As a user <br>
So I can find food available in my local area <br>
I can see a list of food in my area <br>

As a user <br>
So I can see what items are available in my area <br>
I can see items near my location on Google Maps <br>

As a user <br>
So I can receive recipe ideas based on food items in my area <br>
I can view a recipe suggestions <br>
