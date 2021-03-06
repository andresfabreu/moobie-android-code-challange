# moObie Android Code Challenge

## About the challenge
This is a code challenge of 7 days duration. Please read all the instructions carefully.

## Setup
Before starting make sure to setup and run our [pairing API code](https://github.com/andresfabreu/moobie-android-pairing-api).

## Requirements
- Must use: 
1. An architecture pattern
2. Kotlin

- Must have at least:
1. One unit test
2. One integration test

## Description
Our pairing API delivers a Car CRUD, in moObie app this CRUD is used in two differents scenarios: 
1. Favorite Screen, display favorited cars
2. Map Screen, display cars near the user

That said the Challenge consist in the development of a component that will be used in these two different scenarios, each scenario have some particularities:
1. Favorite Screen: Display only Car model and brand, does not have a click action
2. Map Screen: Besides the Car model and brand also display the distance between the Car and the user, notice that our backend team was not able to deliver this information, so it'll be calculate in app side.

*ps: The component may or may not have a custom header and footer, based on each scenario. The entry point can be a screen with two button for exemple.

## Submission
Send a link to a public git repo.
