---
layout: post
title: Flight Price Tracker - My first Data Science Application
---

Its been a while I started experimenting on the full stack side of the data science paradigm.
And let me be honest, I failed many times before being able to complete a small DIY project end to end. Challenges were -where to get the data from, what objective to solve for, getting stuck at a weird bug, unable to solve the interaction between two tools, other important priorities at work. I was never able to complete a working MVP end to end.

And hence, this post is special. Very special for me because I have learned things in both Technical and Personal side of my life.

Lets start with the geeky stuff :

The app is directed for end user usage to find out the price trends between Domestic Flights in India across major Origin Destination Pairs. Not a great value add, but a good practice project to start the soup stirring with all the tech ingredients. It is currently restricted to larger airports and only direct flights.

Tech Stack - Mongo DB, Python , Pandas, Scikit, Flask , Bootstrap , Jinja, Plotly , CSS + HTML , Javascript, AJAX

Scrape daily flights pricing data into MongoDB. Used Pandas mainly for data wrangling, Scikit for modelling, Flask as the web framework along with Jinja and Bootstrap for templates, Plotly charts and Javascript for client side single page ajax queries.

Here is a snapshot of the Landing page - 

![alt text](/images/FPT-Home-Page.png "Flight Price Tracker Home Page")



The OD pair page -  For choosen Origin and Destination gives average price (Y axis)  when booked # of days in advance (X axis) along with some other statistics.

![alt text](/images/FPT-OD-Pair.png "Flight Price Tracker OD Price Variation")



Flight Price Predictor - For a choosen Flight Date, OD pair and the date when you plan to book the ticket predicts the ticket fare by FLight ID's on that route.

![alt text](/images/FPT-Price-Tracker.png "Flight Price Tracker")


Most of the technologies were new to me except mongodb and python. And it took a good 3 months to reach here with a regular day job. Thanks to google, stackoverflow along with a few friends and colleagues who helped me fix bugs and give feedback.
I am not going to deploy this yet publicly. Let the feedback flow.

Next steps include explore AngularJS, React frameworks and strengthen the basics in Javascript to ensure faster turnaround times for an app like this.
