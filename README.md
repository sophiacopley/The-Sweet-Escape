# SENG201 Project - The Sweet Escape - README
Welcome to The Sweet Escape.
This README file includes some useful information to help you build our source code, clone the project and run the program from the terminal.

## Authors
- amc525
- sco207

## Attributions for works
- https://nz.pinterest.com/pin/confetti-gifs-find-share-on-giphy--1117948307475324447/
- https://giphy.com/explore/loser
- https://www.shutterstock.com/search/hair-bow?image_type=vector
- https://www.istockphoto.com/vector/sugar-packet-icon-flat-design-gm1387705862-445570676
- https://depositphotos.com/vectors/money-clipart.html
- https://www.dreamstime.com/illustration/broken-store-window.html


## Prerequisites
- JDK >= 17 [click here to get the latest stable OpenJDK release (as of writing this README)](https://jdk.java.net/18/)
- *(optional)* Gradle [Download](https://gradle.org/releases/) and [Install](https://gradle.org/install/)


## What's Included
This project comes with some basic examples of the following (including dependencies in the build.gradle file):
- JavaFX
- Junit 5

## Importing Project (Using IntelliJ)
IntelliJ has built-in support for Gradle. To import your project:

- Launch IntelliJ and choose `Open` from the start-up window.
- Select the project and click open
- At this point in the bottom right notifications you may be prompted to 'load gradle scripts', If so, click load

**Note:** *If you run into dependency issues when running the app or the Gradle pop up doesn't appear then open the Gradle sidebar and click the Refresh icon.*

## Run Project 
1. Open a command line interface inside the project directory and run `./gradlew run` to run the app.
2. The app should then open a new window, this may not be displayed over IntelliJ but can be easily selected from the taskbar

## Build and Run Jar
1. Open a command line interface inside the project directory and run `./gradlew jar` to create a packaged Jar. The Jar file is located at build/libs/amc525_sco207_TheSweetEscape.jar
2. Navigate to the build/libs/ directory (you can do this with `cd build/libs`)
3. Run the command `java -jar amc525_sco207_TheSweetEscape.jar` to open the application.

## Run Tests
1. Open a command line interface inside the project directory and run `./gradlew test` to run the tests.
2. Test results should be printed to the command line