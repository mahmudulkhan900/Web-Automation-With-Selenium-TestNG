# Web-Automation-With-Selenium-TestNG

## Why we use Selenium TestNG for Automation?

Selenium is a popular open-source testing tool widely used for automating web browsers. It allows developers and testers to automate web-based applications' testing across multiple browsers and platforms. Selenium provides a set of APIs to interact with web elements and manipulate their properties and behaviors, making it an ideal tool for automating UI tests.

TestNG is a testing framework for Java that is designed to be more flexible and powerful than JUnit. It supports a wide range of testing functionalities, including unit, integration, and end-to-end testing, as well as parallel execution, data-driven testing, and reporting. TestNG is often used with Selenium to create robust and scalable test automation frameworks.

## Technology used:
- Selenium Webdriver
- TestNG Framework
- Java
- Gradle
- Intellij idea
- Allure

## How to run this project

- Clone this project
- Hit the following command into the terminal:
 ```gradle clean test```
 
- For generating Allure Report use these commands:
```allure generate allure-results --clean -o allure-report``` and
```allure serve allure-results```

## Scenerio:

- Login to orange hrm demo site: https://opensource-demo.orangehrmlive.com/
- Create 2 new employees and save it to a JSON list
- Now go to PIM dashboard and search by 1st user name. Assert that the user is found.
- Now click on the user from the search table and update id by random userid
- Now again search the user by new user id from the PIM dashboard menu and assert that the user is found
- Now logout from admin and login with the 2nd user from your JSON list
- Now click on My Info menu
- Select Gender and Blood Type and save it
- Click on contact details and input address and email
- Logout the user

## Test case check list based on the Scenerio:
- Admin Login with Invalid credential. 
- Admin Login with valid credential.
- Create employee without username.
- Create first employee.
- create second employee.
- Search existing employee with invalid name.
- Search employee with valid name.
- Update employee Id by random Id.
- Search employee again with updated employee id.
- Logout Admin.
- Login second user with valid credential. 
- Insert the second user's Gender, Blood, Address and email. 
- Logout second user.

## Testcases for this Report

https://docs.google.com/spreadsheets/d/1AIbUN8rDromlwEId2qwQtt1DgpCdQ_15Nd_4tB1u-7A/edit?usp=sharing


