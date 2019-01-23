# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview
SpenderMap is a web-based heatmap that shows a user's transactions overlaid on a geographical map of where their spending has occured. 

SpenderMap works by prompting a user to create a account and uploading their transaction history through a typical CSV file. The webapp reads the location information as recorded in the transaction detail log and feeds the data through a Google API that returns lat/long coordinates. The coordinates, along with business information, is displayed on a MapBox generated map with rich colorization that shows pockets of spending clusters that "break-up" as users zoom and interact with the map.

### Features
* Display Map: Ability to visually examine transaction data on a generated location map
* Infocard: Clickable entries that display individual business information when prompted on map
* CSV Readability: Data sourced from user-provided CSV file
* User Login: Authentication system for CSV file security
* Transaction Search: Lightly queryable transaction database

### Technologies
* HTML
* Bootstrap
* MapBox
* Java
* Thymeleaf
* SQL

### What I'll Have to Learn
SpenderMap will require several linkages that I will need to understand how to configure. Firstly, Mapbox is written in JavaScript, but MapBox does contain a Java API that should allow me to send information for the map rendering process. Similarly, I will have to setup the Infocards to source their data from some type of business database resource. Next, the CSV file will have to be stored and parsed to obtain the transaction data -- I'm hoping to reserve-engineer LaunchCode's TechJobs exercize that made use of a similar feature. Additionally, I will have to make sure that a User's CSV file is linked permanently to the User for security reasons and for website revisits. Finally, I will have to create a page that allows the converted transactional data to be queried to enhance the program's usefulness to the User.

### Tracker
I'm planning on using Trello to track this project: https://trello.com/b/ZFcWtLCn/spendermap
