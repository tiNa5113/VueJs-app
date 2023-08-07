# simple-vue-app


This Repo demonstrates the use of the following in vuejs
1. Vue Routing
2. Components
3. Communication between Components ( Parent to child component )
4. Axios Library to make HTTP calls

The Application is deployed in


## Prerequisites

### Install NodeJS [![Generic badge](https://img.shields.io/badge/Prerequisite-NodeJS-blue.svg)](https://nodejs.org/en/)

Refer https://nodejs.org/en/ to install NodeJS

### Install Vue Cli [![Generic badge](https://img.shields.io/badge/Prerequisite-VueCli-blue.svg)](https://cli.vuejs.org/guide/)

Install Vue Cli Node Package Globally using the following Command.

```bash
npm install -g @vue/cli
```
## Cloning and Running the Application

Clone the application to local

Go into the project Folder and install the npm packages using the following command
```bash
npm install
```
Run the following command to run the application
```
npm run serve
```
The Application runs on **localhost:8080**

## Application Design

### Views and components

**Customers** : This View Displays a list of customers and gets the data from a json from assets folder

**CustomerDetails** : This View Displays the Details of a single customer and gets the data from a json from assets Folder

**Display** : Display component displays the name of the selected customer in **Customers** View. **Display** is a child component of **Customers** View



The Application has 2 endpoints

**/customers** : The ties to *Customers* View

**/customerdetails** : This ties to *CustomerDetails* View

