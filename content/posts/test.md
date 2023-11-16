+++
title = 'Merchant Bot'
date = 2023-11-14T17:28:28-05:00
draft = false
+++

[Github link](https://github.com/dominicf2001/merchant)

## Introduction

This project has been one of my favorites. It started quite simple. I wanted to create a discord bot to manage a small economy, and deploy it into a server I am active in. The goal was to make the bot improve average user activity, and just have some fun.

The first iteration included a database to store users, items and the relationship between users and items. Each user had a balance and an inventory. They could work everyday in order to earn more currency in order to purchase items in the shop. The items started basic: mutes/unmutes, dye, a nametag and more. Each item peforms some basic action in the server, such as muting a user, or changing the color of a nickname. The intention was to create devious interactions between users, while keeping things fair and fun.

Since the server I deployed in was active, I was able to immediately have users. It wasn't long before suggestions starting pouring in, which got me thinking about directions the bot can take. One suggestion I got thrown was for a gambling system. I liked this idea, but I knew too many other bots already implemented this. This caused me to think about ways to add a unique twists. What came to mind was a simulated stock market. This idea seemed excellent, but there was one problem. How would stock prices be determined? Immediately I connected this thought to my initial goal: improve average user activity. If I made stock prices determined by user activity, then ideally this would incentivize users to try to increase server activity.

Thinking about this idea more, I settled on the approach of associating a stock with each user in the server, and having its price be determined by that users activity. Thus, if a user invested in the stock of another user, they would be rewarded for making that user more active.


