---
layout: post
title: Going Offline With Progressive Web Apps
date:   2016-06-01 09:00:00
author:
  name: "Dave"
  username: "davatron5000"
categories:
  - Features
---
We're happy to announce DayTrip is now a fully responsive [Progressive Web App](https://developers.google.com/web/progressive-web-apps/), a combination of new web technologies championed by Google Chrome. Starting this week, Android users (~13% of our active user base) who use DayTrip more than once will eventually be asked if they want to install our web app to their Home Screen. That's important real estate for a small startup like ourselves.

![Image of Chrome for Android's Add to Homescreen experience](/assets/img/pwa.jpg)

## What's this mean for me?
Progressive Web Apps are aimed at giving fast, reliable, native "app-like" experiences. After being installed, you'll be able to launch DayTrip from your Home Screen and it will behave like an app you downloaded from an App Store.

In addition to that, Progressive Web Apps improve your offline experience. Getting people offline is major part of why DayTrip exists. If you find yourself in the woods with bad cell signal, previously viewed pages on your device will be cached and available offline.

## Why not just go native?
"Why not just go native?" is a good question and frequent feedback request. Truth be told, we actually headed down that direction. We built an API and prototyped multi-platform mobile clients but hit a wall where we had to make an important decision whether or not to continue development.

For such a small team, diverting resources to create native clients meant the core product wasn't being worked on. Our prototypes never wowed us and it seemed like we were making herculean efforts to create native clients that were only about 10% different than the responsive web product.

For our situation, it made more sense to stick to our wheelhouse, avoid [App Store drama and disillusionment](https://marco.org/2014/07/28/app-rot), and focus on improving and expanding the flagship web product. Thankfully, Progressive Web Apps were on the horizon and match our business model perfectly.

## What's next?
In the short term we'll be improving our basic offline experience and figuring out how we can use Service Workers (a new browser technology) to make the DayTrip speedier and more useful.

In addition to Google Chrome, Mozilla Firefox and Microsoft Edge have also shown interest in supporting Progressive Web Apps. The lone hold out right now is Apple's Safari. While that excludes a majority of our mobile users, we're bullish on the future of Progressive Web Apps. We're fans of an App Store model where the relationship between a device and an app, just like [human interest](http://trentwalton.com/2013/08/12/human-interest/), grows over time.
