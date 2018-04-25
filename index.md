# Table of Contents

* [About Learning Comrades](#about-learning-comrades)
* [User's Guide](#user's-guide)
  * [Landing Page](#landing-page)
  * [Login Page](#login-page)
  * [Profile Page](#profile-page)
  * [Create Study Session Page](#create-study-session-page)
  * [Upcoming Study Session Page](#upcoming-study-session-page)
* [Developer Guide](#developer-guide)
* [Development Details](#development-details)
* [Community Feedback](#community-feedback)
* [Deployment](#deployment)
  
 
# About Learning Comrades

Learning Comrades is a UH Manoa ICS 314 [organization](https://github.com/learningcomrades) driven to build a web application that allows ICS students to improve their academic career and find new comrades to assist them in this treacherous journey. We humans are social creatures that want thrive on interaction with others. Learning Comrades is a tool to provide the ICS undergraduate community a new way to learn and socialize.

# User's Guide

## [Landing Page](http://learningcomrades.meteorapp.com/#/)
This is the homepage where students can look at the current avaiable study sessions according to their course that they are struggling in.

![](images/landing_page2.png)

## [Login Page](http://learningcomrades.meteorapp.com/#/signin)
The user can register an account and input their login credentials.
![](images/login2.png)

## [Profile Page](http://learningcomrades.meteorapp.com/#/add)
The user can create and update their profile 
![](images/profile2.PNG)

## [Comrades](http://learningcomrades.meteorapp.com/#/list)

![](images/comrades.PNG)

## [Create Study Session Page](http://learningcomrades.meteorapp.com/#/create)

![](images/create.jpg)

## [Upcoming Study Session Page](http://learningcomrades.meteorapp.com/#/view)

![](images/upcoming.jpg)

# Developer Guide

First, install meteor.

Then in your command line, cd in to your github directory and run this command

```
$ git clone https://github.com/learningcomrades/LearningComrades.git
```

Then cd in to the learning comrades application's app directory and run this command.

```
$ meteor npm install
```

Lastly, you can run it with meteor with:

```
$ meteor npm run start
```

Learning Comrades application will be avaiable at [http://localhost:3000](http://localhost:3000).

# Development Details

[Milestone 1](https://github.com/learningcomrades/LearningComrades/projects/2) 

[Milestone 2](https://github.com/learningcomrades/LearningComrades/projects/3)

[Milestone 3](https://github.com/learningcomrades/LearningComrades/projects/4)

# Community Feedback

We chose five ICS students from different class standings to test our app. They understand that ICS is a hard course and some need additonal help outside of a professor's office hours. They enjoyed the simple to use UI where one can quickly create a study session page and coordinate a time and place to study. They find it simple to browse through other user's profiles to quickly get a first impression on them based on their profile picture and the courses that they have already taken.

One tester offered their concerns, stating that this app would have a more widespread appeal if it weren't only for ICS students. Currently the app allows anyone to make an account, however it only offers classes based off on the ICS curriculum. There is the other notion that people wouldn't want to move from their current desired platform (ex. discord, facebook, etc.), as it would take time for students to pick up on Learning Comrades. This could be resolved by promoting this application to incoming ICS students. Students new to discrete math and programming will be able to use this app to coordinate study sessions. 

# Deployment

[Deployed Web Application](https://galaxy.meteor.com/app/learningcomrades.meteorapp.com)

