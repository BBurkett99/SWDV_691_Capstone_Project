SWDV_691_Capstone_Project

Design: Proposed Project Idea and Minimum Viable Product (MVP)

Problem: Knowing how to understand and keep track of basic medical test from home

Solution: The Health Tracker Application
Purpose of Project: This web application is specifically designed for users to input and store the results of simple medical tests that can be performed at home. These tests would include blood pressure and glucose readings along with body mass index results from the user’s weight and height. Users would be able to review the results of these test and see for example how their blood pressure is trending. This application would also have warnings for when the reading from these tests were found to be out of the normal ranges. This could be a help for people who may not know what numbers qualify for high blood pressure.

Concept: The idea of the process is to use HTML, CSS, and PHP to create the user interface and store the data in a Heroku database. This data can then be used to populate a graph to show how the results are trending.

User Personas: The three chosen personas I have used will vary in age, occupation, and gender. People with pre-existing medical conditions like diabetes, hypertension, or who are overweight are very likely to benefit from this web application. Also, this can benefit people who are worried about having these medical conditions in their family tree, since two of the previous mentioned conditions are considered to be hereditary. 

Costs of the Project:  The web application that is being developed is to help educate the public. High blood pressure and obesity affect many people in this country, any kind of web application that can help combat these issues has the potential for a large following. Once a following has been established advertisements can also be added to the website to create revenue.

How Project Solves Users’ Problems: The web application will hopefully help users become more organized and educated about their health. This type of application could help a very wide range of users. It could be used by someone who just wants a convenient way of keeping track of their high blood pressure or BMI. However, the application would have many features that could help people communicate important information to their doctors. By following the guide lines of this application and completing these three tests on a weekly basis the user could possibly see a correlation of blood pressure readings going up or down depending of fluctuation of their weight.

How Will Users Interact with the Web Application:  As a user, they would begin by logging in and bringing up the home page. After viewing the home page, the user will then decide on what type of test they will be performing and click on the desired link. Once they have completed one of the tests, they would then input the results. This would be done for all three of the different tests. Once some data is collected the user will be able to see their results in a graph section of the web application. 

Minimum Viable Product (MVP)

A high-level overview
This web application will require certain features to be able to solve the user’s problems and help them understand what the normal range for the results of these three tests are. There will need to be a login and a home page to help direct the user to the test input pages. These data inputs would then be stored in a database to be used to compare to future readings and provide the results in a graph. This way it will be easier for the user to see trends (good or bad) in their results. 

Minimal set of features 
The minimal set of features to be able to provide a workable solution will be the login page, the home page with three links to the test input pages. This will include the Blood Pressure Inputs page, the Glucose Inputs page, and the Weight/BMI inputs page. A database will be needed to store all of the different readings and be available to used for each test to set a graph of trending data. 

A high-level architecture
There are several service layers associated with this web application, the first service layer would be used for the login page. Some of the other service layers will be used for storing the data inputs from the user then transferring them to the database. 

A high-level description of the data 
The data that will have to be managed for this web application is all of the user inputs for all three of the at home medical tests pages. This data will have to be separated by the three different tests. Then the data will need to be separated by the date it was recorded. An example of this could be the blood pressure data inputted in on the first week of July will need to be stored in the database and have a relationship with only the blood pressure input page and the blood pressure results (graph) page.
