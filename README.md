# PromillePartnerSamlet

This repository is a collection of repositories that belong to the "PromillePartner" project.
You will find all of the API's, classes and class repositories in the BackEnd folder.
The frontend folder contains all of the front end code and styling.
In the Postman folder, you'll find postman tests of the API's and in the PromilleTest folder, you'll find Selenium UI testing of the frontend pages.
In the raspberry pi folder, you will find all of the code that is run on the raspberry pi 5.

What is PromillePartner?:
PromillePartner is a project meant to help you pace yourself while drinking. The purpose is that you can in advance plan out how drunk you want to be and make sure you don't exceed your targetted alcohol level. You can achieve this by creating a personal drinking plan on the website and by keeping check on your alcohol levels with the alcohol sensor. 

How to use Promille Partner:
1) Set up your raspberry pi and alcohol sensor by following the pdf guide "How to set up the raspberry pi and sensor"
2) Navigate to our website: https://nice-ocean-08d657c03.4.azurestaticapps.net/
3) In the navbar, navigate to the "Person" tab and input your gender, age and weight. Your ID is given to you when you click Save. This will be used in the Drukplan.
4) In the navbar, navigate to the "Home" tab and input your Id in the first field. Then fill in your current promille, wanted promille, length of drukplan and choose from the list of drinks.
   b) as a bonus, you can navigate to the "Tilfældig Cocktail" tab to get a random drink suggestion.
5) Click the calculate button and you will get a drukplan.
6) When you are ready to start drinking, Click the "Start Timer button" and take your first drink. Then take the next drink once the specified amount of time has passed etc
7) If you want to check if your promille is still below 0,5(the legal driving limit in Denmark), run the script on the pi.
8) Blow into the alcohol sensor and go back to the website and navigate to the "Promille" tab on the navbar.
9) If the page hasnt refreshed with your latest reading, click the "Hent seneste måling" button.
10) and lastly, DO NOT use this project to drink and drive. :)
