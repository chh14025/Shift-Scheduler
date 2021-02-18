# SHIFTLY

## Project Description

A Web Application built using Angular and Java/Spring that allows dynamic scheduling to reduce management overhead!

Deployed: http://team-reston-shift-scheduler.s3-website.us-east-2.amazonaws.com/

## Technologies Used

* Hibernate 4.3.11.Final
* Java 1.8
* JUnit 5.7.0
* Spring ORM
* Spring MVC
* PostgreSQL 42.2.18
* Jenkins
* AWS EC2
* Angular 2+
* Log4J 1.2.17
* Mockito 1.8.4

## Features

List of features ready and TODOs for future development
* An employee can login to view their weekly schedule, daily shifts, and assigned tasks. Employees can view announcement board messages posted by managers, send private messages to other users, as well as updating availabilities.
* A manager can login to view/post new messages on the announcement board, view/edit daily shifts by assignment positions to available employees. Managers can also post a new schedule with updated employee assignments. Lastly, managers also have the ability to send direct messages as well as editing their availabilites.


## Getting Started
   
Start by cloning the entire repository to your local machine.

Frontend Installation:
Head to the p2-RESTon-angular directory and find the command "npm install" to install all of the required packages. After all necessary packages have been installed, run the command "ng serve -o" to see the front-end portion of the application.

Backend Installation:
Although there are several ways to deploy the back-end portion of this application, the currently deployed version of the application leverages docker/jenkins. If/when you deploy the back-end, ensure that the front-end API calls (found within the /services folder of the Angular application) are pointing to your deployed URL.

