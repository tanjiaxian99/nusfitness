# nusfitness

A NUS Facilities Manager written using MERN Stack and Telegram Bot API.

> v0.3.0 has now been deployed. You may visit the NUSFitness website [here](https://jereldlimjy.github.io/nusfitness/) and our Telegram Bot @NUSFitness_Bot [here](https://t.me/NUSFitness_Bot).

- [Frontend codebase](https://github.com/jereldlimjy/nusfitness)
- [Backend codebase](https://github.com/jereldlimjy/nusfitness-api)
- [Telegram Bot codebase](https://github.com/tanjiaxian99/nusfitness-telebot)
- [API Documentation](https://tanjiaxian99.github.io/nusfitness-docs/)

## Table of contents

- [General info](#general-info)
- [Screenshots](#screenshots)
- [Features](#features)
- [Technology](#technology)
- [Setup](#setup)
- [Status](#status)
- [Contact](#contact)

## General info

The better NUS facilities manager for all your workout needs.

## Screenshots

![NUSFitness website: Dashboard page](https://imgur.com/6ABVg75.png)

![NUSFitness website: Bookings page](https://imgur.com/yn9c2tV.png)

![NUSFitness website: Timetable page](https://imgur.com/jCDfM1Y.png)

![NUSFitness website: Profile page](https://imgur.com/DdmaqkK.png)

<p float="left">
    <img src="https://imgur.com/nKrTmih.png" width="24.6%">
    <img src="https://imgur.com/u2T90In.png" width="24.6%">
    <img src="https://imgur.com/vMx5VKE.png" width="24.6%">
    <img src="https://imgur.com/8W6BKgw.png" width="24.6%">
</p>

Click [here](https://imgur.com/a/jNbATI9) for more screenshots!

## Features

A **Website** that contains a database for all the bookings in all NUS gym/swimming pool facilities. Beyond allowing students to book a slot, other features include a dashboard that displays current and previous gym traffic, importing timetables from NUSmods to filter out slots that clash with the student’s timetable and an account management system to manage previous bookings and cancellations.

The **Telegram Bot** provides an easy to use interface for students to make a booking for NUS gyms/pools. It will also allow for limited access to the dashboard without any filtering.

Given the ubiquity of Telegram amongst NUS Students, our objective is to port over as much of the functionality as possible from the web app.

1. Website

   - Real-time booking system
   - Dashboard that displays current and previous gym/pool traffic, aggregated by a date range that users can specify. Users can also filter by day of the week.
   - Import timetable from NUSmods to filter out clashing slots
   - View NUSMods timetable that includes both modules and booked slots
   - An account system for each user containing their previous bookings

2. Telegram Bot
   - Real-time booking system that is synced with the website
   - Dashboard that displays current and previous gym/pool traffic, aggregated by selected dates.

## Technology

- MongoDB
- Express
- React
- Node.js
- Telegram Bot API
- Material-UI
- Heroku

## Setup

**Frontend**  
Clone the [repository](<(https://github.com/jereldlimjy/nusfitness)>) onto your local machine. Install [Node.js](https://nodejs.org/en/download/).

Install Yarn by running

     npm i --global yarn

Install dependencies by running

     yarn install

Once done, start the app with

    yarn start

**Backend**  
Clone the [repository](https://github.com/jereldlimjy/nusfitness-api) onto your local machine. Install [Node.js](https://nodejs.org/en/download/).

Install dependencies by running

    npm install

Once done, start the app with

    npm start

**Telegram Bot**  
Clone the [repository](https://github.com/tanjiaxian99/nusfitness-telebot) onto your local machine. Install [Node.js](https://nodejs.org/en/download/).

Install dependencies by running

    npm install

Once done, start the app with

    npm start

## Status

Project is stable at v0.3.0.

## Contact

Created by [Jia Xian](https://www.linkedin.com/in/jia-xian-tan-5490721a0/) and [Jereld](https://www.linkedin.com/in/jereld-lim/)
