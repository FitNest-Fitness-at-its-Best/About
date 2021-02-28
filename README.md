# FitNest - Fitness At Its Best

- [FitNest - Fitness At Its Best](#fitnest---fitness-at-its-best)
  - [Summary](#summary)
  - [Introduction](#introduction)
  - [The App](#the-app)
    - [The Features](#the-features)
      - [Auth](#auth)
      - [Home](#home)
      - [Foodlog](#foodlog)
      - [Analytics](#analytics)
    - [The Business Model](#the-business-model)
    - [Future Prospects](#future-prospects)
  - [Challenges we ran into](#challenges-we-ran-into)
  - [Contributions](#contributions)
  - [Links](#links)
  - [Extras](#extras)

## Summary
An app which promotes health and healthy eating with the help of AI and analytics!
## Introduction
Due to its drastic increase during the past decade, obesity is becoming an epidemic
phenomenon in most developed countries. 

The fact that more than 33% of adults and 16% of children are obese has proven to 
be one of the biggest public health challenges to the general  population and social 
welfare. Unfortunately, obesity has still not been controlled effectively.

Also, due to COVID-19, people have been mostly eating at their homes only, *leading
to the illusion that they’re eating healthy*. The amount of preservatives they have
been intaking missing from fast food is immense. Mindless eating while working from
home can be a disaster to one's health.

This is why we propose a **Food Detector - FitNest for AngelHacks 2.0**

## The App
Based on a photo taken by the user, the app detects the food present and respectively
finds nutritional information for the given food. The user can then log this data into
a virtual diary which would help keep track of their calories consumed.

### The Features

#### Auth
* Login with Google 😆
#### Home
* it show the recent Medium Articles under "food" topic
* User can read the article within the app as a `WebView`

#### Foodlog
* People can upload photos of what they ate
* Our model detects the food item and also shares the related calories, carbs, protien etc value associated with it
* They can edit the serving size and the calories, carbs etc values change accordingly
* We also maintain a flag to improve the default quantities suggested by people over time
* Users can also see their foodlog history, along with any pictures they uploaded

#### Analytics
* We show the graphs for calories, protiens carbs and fats
* We also show a **Health Score** for all the people, which is based on a number of factors
  * Calories
  * Carbs 
  * Fats
  * Protiens
  * Sleep
  * Steps
* We get the sleep and step data from Apple Health and Google Fit

### The Business Model
*Our Business Model and the features that we've added makes us unique!*

* All the applications are paid for premium users. This makes it difficult for the common user to use it.
* We have made our business model different from all the apps out there. 
* Food Delivery companies(Swiggy/Zomato/Uber Eats) would definitely want to use this for showing their users 
what could they order according to their health demands. 
* This has a very high probability of their sales rising 
* Local businesses which sell healthy food could post an ad in our application for all the health freaks out there!

### Future Prospects
Competition can make wonders happen!  If staying healthy is difficult by the means of percentage, 
percentile it is 😉

We plan to introduce a **social feed** where you could compare your health score with your friends/family members!
* Craving for a cheese burst pizza? Look your best friend Amy had salad for lunch! 👀
* And maybe you could plan cheatdays with your gang together somedays later!! 😉


## Challenges we ran into
1. Ooof, we thought searching for Dataset would be an easy thing. THERE IS NO DATASET ON ANY SITE WHICH COULD. WE ENDED UP TRYING SO MANNYYY STUFF LIKE SCRAPING, IMAGINE GETTING SANJEEV KAPOOR'S FACE FOR MASALA DOSA! :pensive:
SHOW INDIAN COOKED FOOD AND ITS CALORIES.  Scraping it via the internet and cleaning it was a BIG HELL OF a task.
2. As beginners, we learnt many things during this short duration of time.
3. Colab gets its runtime restarted, and the model had to be run thrice(and it takes so much time to do so).
4. The model had to be optimized a lottttt, initially we were getting outputs in 5-10 second intervals! 👀
5. Integrating the model with backend was quite challenging, especially when none of us had experience ever of loading it directly......
6. Finally deciding metrics on how to get a health score was something that made us learn and research a lot....it was fun, yet exciting....


## Contributions
* Machine Learning, Data Preparation- Vasudha 
* Backend, deployment - Abhishek
* Application Development, UI Designs, Workflow - Siddhartha Varma
* Scraping & Data collection - Vasudha

## Links
* [ML Repo](https://github.com/FitNest-Fitness-at-its-Best/Machine-Learning)
* [Backend Repo](https://github.com/FitNest-Fitness-at-its-Best/Backend)
* [App Repo](https://github.com/FitNest-Fitness-at-its-Best/app)
* [Figma Link](https://www.figma.com/file/Ywmx3rJWdPNaqqPJLntwDW/Fitnest?node-id=0%3A1&frame-preset-name=iPhone%2011%20Pro%20Max)

## Extras

* Workflow Diagram (Raw Diagram)
  
![excalidraw is the best](screenshots/image%201.png)

