---
layout: '[layout]'
title: How configure the time in Appservices 
date: 2020-01-20 11:05:47
tags: Azure
---
In this opportunity we will see how to change the date of an app services, we sometimes get a headache since we need to put the app services in our schedule, usually the app services have UTC schedule.
  ![](/images/timer.jpg)
To make this change we will proceed to go to the configuration and proceed to go to New application Setting
  ![](/images/timer2.jpg)
When we are in New application Setting in the name we will add WEBSITE_TIME_ZONE and in its respective value Central America Standard Time we give OK we save the changes and restart the environment
 ![](/images/timer3.jpg)

We go to the console and verify that the app services time is in our time zone
 ![](/images/timer4.jpg)