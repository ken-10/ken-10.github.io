---
layout: project
type: project
image: images/
title: Bowfolios App
permalink: projects/bowfolios
# All dates must be YYYY-MM-DD format!
date: 2020-06-07
labels:
  - Flutter
  - Dart
  - Firebase
summary: A mobile app implementation of Bowfolios made by Philip Johnson. This app allows users to view, modify, and search profiles, projects, and interests.
---

# Table of Contents
* [Overview](#overview)
* [Project Links](#links)
* [Project Milestones](#milestones)
* [User Guide](#guide)
* [Developer Guide](#devguide)
* [Team Members](#members)

<a name="overview"></a>
# Overview
BowFolios Mobile is an mobile app of the original BowFolios web application. Users have the ability to create a profile, add interests, and profiles. It provides the ability to view and modify profiles, projects, and interests. It is a quick way to find other UH Manoa students with the same interests and view their previous and current projects. 

For Milestone 1, we created the user interface for the login, create account, profiles, interests, projects, drawer navigation, and set up firebase for backend data storage and user authentication.

For Milestone 2, we plan to implement backend features to the profiles, interests, and projects page. We also want to route the widgets in the drawer navigation.

For Milestone 3, we plan to implement a search page that filters profiles by interests, user profiles page, show profile cards on profiles page, show profiles and projects based on chosen interest on the interests page, and show project cards on projects page.

<a name="links"></a>
### Project Links
* [GitHub Project Board](https://github.com/yertnek/bowfolios/milestones)
* [GitHub Source Code](https://github.com/yertnek/bowfolios)

<a name="milestones"></a>
# Project Milestones
### [Milestone 1](https://github.com/yertnek/bowfolios/milestone/1)
The purpose of Milestone 1 is to have a partially working version of BowFolios.

### [Milestone 2](https://github.com/yertnek/bowfolios/milestone/2)
The purpose of Milestone 2 is to improve upon features made in Milestone 1. Main goal is to implement backend functionality.

### [Milestone 3](https://github.com/yertnek/bowfolios/milestone/3)
The purpose of Milestone 3 is to implement final features and fix bugs. Main goals are to implement a proper working profiles, projects, interests, and search page.

<a name="guide"></a>
# User Guide

### Login Page
The login page is presented to first time users or logged out users when they open the app. They have the option to login with valid credentials or redirect to the sign up page.

<img src='./doc/login_mockup.png'>

### Sign Up Page
The sign up page is for first time users who do not have an account. They can create an account by providing a valid email, username, and creating a new password.

<img src='./doc/signup_mockup.png'>

### Profiles Page
The profiles page is presented to returning users when they first open the app. The profile page shows a list of users and the projects 
and interests associated with each specific user.

<img src='./doc/profile_mockup.png'>

### Projects Page
The projects page shows a list of the projects and the users and interests associated with each specific project.

<img src='./doc/projects_mockup.png'>

### Interests Page
The interests page shows a list of the interests.

<img src='./doc/interests.PNG'>

### Drawer Navigation
The drawer navigation is used to redirect back home, the users profile page, the add project page, and the search page.

<img src='./doc/nav_mockup.png'>

### User Profile Page
The user profile page allows users to edit their credentials and change their profile picture.

<img src='./doc/user_profile_mockup.png'>

### Add Project
The add project page allows users to add a project to the Bowfolios application.

<img src='./doc/add_project.PNG'>

### Search Page
The search page filters profiles by interests.

<img src='./doc/search_page.png'>

<a name="devguide"></a>

# Developer Guide
This section provides information on how to get the application to run on a developers local machine.

### Installation
First, follow the steps [here](https://flutter.dev/docs/get-started/install) to get flutter set up.

Install a virtual mobile device from here:
* [Android Studios](https://developer.android.com/studio)
* iOS Emulator (Mac Only) You must download and install XCode from the App store.

Once flutter is installed, clone the [repo](https://github.com/yertnek/bowfolios).

Next change directories into the projects folder and run the command:
```
$ flutter pub get
```

Make sure you have a virtual device running, and start the application by running the following command:
```
$ flutter run
```
The application will take a little while to start up, but once it does you should land on a login page and you are all set to use the app!

<a name="members"></a>
# Team Members
* [Trey Sumida](https://github.com/trey-sumida)
* [Ken Tung](https://github.com/ken-10)




