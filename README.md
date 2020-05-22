# coding_challenge_IIII

Instructions:

Fork this repo.

Clone the repo and push up your changes and share link.

Using Protractor or WebDriverIO Bonus points for leveraging a BDD tool.

Create a branch and name it with your "{firstname_lastname}_LL_challenge"
Make sure to update your README to show how to run your scripts
Fulfill the following two scenarios
Once complete push your branch up

Feature: Automate
     As an Engr. Candidate
     I need to automate http://www.way2automation.com/angularjs-protractor/webtables/
     So I can show my automation capabilities

Scenario: Add a user and validate the user has been added to the table

Scenario: Delete user User Name: novak and validate user has been deleted

# Solution

For this solution several dependencies will be needed:

  "chai", 
  
  "chromedriver",
  
  "selenium-webdriver",
  
  "cucumber"

All them will be installed using NPM.

Before doing the setup, validate you already have installed **NodeJS** (6 or high).
Also validate that chrome browser is installed.


**Setup**

First clone or download this repo.

Validate there is a folder "**features**"

Validate the file **way2automation.feature** inside folder "**features**" 

Validate the file **way2automation.js** inside folder "**step_definitions**

Validate the file **package.json**


When you have this structure validated open a command console and go to the root directory with the **package.json** file.

Then run the command:

**npm install**

This will create all the project structure for the "**node_modules**" folder and will create a **package-lock.json** file.


Finally run the command:

**npm test**

This will make a new chrome browser window to appear and run the 2 scenarios for the test.
