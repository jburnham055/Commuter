# Commuter
# Commuter

## Overview

**Commuter** is a web application designed to help college students find other students with similar commuting routes. Students can post information about their commute, including their hometown, days they are on campus, and typical arrival time. The application then matches students who have similar schedules and routes so they can potentially share rides.

The goal of Commuter is to make commuting to college more convenient, affordable, and social while reducing the number of individual vehicles traveling to campus.

## Features

- Create a commuter profile
- Enter your hometown or starting location
- Select the days you commute to campus
- Enter your typical arrival time
- View students with similar commuting routes
- Find potential carpool partners
- Compare commute schedules
- View basic information about potential matches
- Update or remove your commute information

## How It Works

1. A student creates an account or commuter profile.
2. The student enters their commute information:
   - Home town
   - Days they are on campus
   - Typical arrival time
3. Commuter compares the student's information with other users.
4. Students with similar routes and schedules are displayed as potential matches.
5. Students can contact a potential match and arrange a carpool.

## Example

A student from **Framingham** who arrives on campus around **8:00 AM on Mondays, Wednesdays, and Fridays** could be matched with another student from a nearby town who has a similar schedule.

This allows the students to coordinate rides instead of commuting separately.

## Technologies

The project can be built using:

- **HTML** - Page structure
- **CSS** - Styling and layout
- **JavaScript** - Application functionality
- **Node.js** - Backend/server functionality
- **Express.js** - Web server and API
- **Database** - Stores student and commute information

## Project Structure

```text
Commuter/
│
├── public/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── server/
│   ├── server.js
│   └── routes/
│
├── database/
│   └── database.js
│
├── README.md
├── package.json
└── .gitignore
