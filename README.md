# FakeTwitter

## Learn programming using Python

FakeTwitter is an application specification, for building you first Twitter-like application in Python.  The purpose of this application is purely educational, to teach/learn how to implement a Python library from scratch, and then add to it a CLI interface, and lastly a Web interface.
The idea of this exercise is to integrate several different aspects of basic programming skills:  from language-specific tricks, modularisation, basic password hashing, CLI usage, and introduce on Web development.

## Components

1. FakeTwitter Library
2. FakeTwitter CLI
3. FakeTwitter Web

## The Library

### User Management (user.py)

1. Create User ```createUser(username, password, firstname, lastname, age)```
2. Delete User ```deleteUser(username)```
3. Get User Data ```getUserData(username)```, password should not be returned
4. Update User Data ```updateUserData(username, firstname, lastname, age)```, username is the lookup parameter
5. Update User Password ```updateUserPassword(username, password)```
6. Validate User Password ```validateUserPassword(username, password)```, returns a boolean telling if the entered combination is either valid or not

### Tweets Management (tweets.py)

1. Create Tweet ```createTweet(username, message)```
2. Get All User Tweets ```getAllUserTweets(username)```, returns a list of tweets
2. Get User Tweet ```getUserTweet(username, tweetIndex)```, returns a single tweet message (a string)

## The Command Line Interface

@TODO (depends on persistence layer)


## The Web Interface

@TODO (depends on a simple http server)
