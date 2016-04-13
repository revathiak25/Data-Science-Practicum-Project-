# Data-Science-Practicum-Project-
Twitter Mining to improve Emergency Relief and response 
========================================================
author: Revathi Anilkumar
date: 28th March 2016


What was I doing? 
========================================================

- Assess the accuracy of predicting the damage caused by disasters through posts on social media
- Why – Helps to allocate resources according to needs and also mobilize manpower as and when required

What was the issue?
- Accessing Twitter Historical Data 

What do I need?
- Analyse any event that took place in last 7 days 


So whats the next best alternative?
========================================================

Goal:
-Develop an application that can analyse a hashtag and provide relief options (i.e. food, travel, shelter) for the areas impacted. 

Objectives for this class:
- Identify any help based hashtag
- Create a classifier that classifies the tweets into three groups - Shelter, Food, Travel 
- For each group - Build an algorithm that identifies specific locations for each post in each category
- Map these locations



Steps to achieve Goal 
========================================================

1. Clean the dataset - twitteR Package
2. Remove any tweets that include prayers, mourning, support etc 
3. Classify the data based on words - Shelter(bed, stay, house, home), Food(food, meal, dinner), Travel(travel, ride, travellers, pick, seats)
4. Identify location based on these sections - Create a list of city names, iterate through the classified data. Map the locations along with UserId

