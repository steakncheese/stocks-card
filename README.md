# stocks-card
This app helps you to easily find stocks in the Canadian stock exhange

# readme-template
comprehensive template for README files

&nbsp;

<div align="center">
<img src="https://github.com/jaredhud/QuikDine-mobile/blob/main/src/img/quik-dine.png?raw=true" alt="QuikDine logo" style="height:80px" />
<br>
Recipe made Easy! - Mobile Repo
</div>
&nbsp;
<div align="center">
<img src="https://badge.fury.io/js/npm.svg"> <img src="https://img.shields.io/badge/compatible-iOS%20%26%20android-blue" > 
<a href="https://spoonacular.com/food-api"> <img src="https://img.shields.io/badge/API-Spoonacular-orange"> </a>
<a href="https://cloud.google.com/vision/"> <img src="https://img.shields.io/badge/API-Google%20Vision-orange"> </a>
</div>

&nbsp;
<div align="center">
<img src="https://github.com/jaredhud/QuikDine-mobile/blob/main/src/img/architecture.jpg?raw=true" alt="QuikDine logo" style="width:100%">
</div>
<!-- <h1 align="center">QuikDine-mobile</h1> -->
&nbsp;
<div>
<a href="https://www.youtube.com/watch?v=kbyUfBJmxLE">
  <img src="https://img.shields.io/badge/DEMO%20-YOUTUBE VID%20%E2%86%92-gray.svg?colorA=5d5d5d&colorB=b30b00&style=for-the-badge" />
<a href="https://github.com/jaredhud/QuikDine-mobile/tree/main/src/img/IU C9 P3 G3.pdf">
<img src="https://img.shields.io/badge/PDF%20-DIGITAL FLYER%20%E2%86%92-gray.svg?colorA=5d5d5d&colorB=ff7605&style=for-the-badge"/></a>
&nbsp;
</div>
## Table of Contents

- [readme-template](#readme-template)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Key Features](#key-features)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Examples](#examples)
  - [Technologies Used](#technologies-used)
  - [Contributors List](#contributors-list)
  - [Contribution Guidelines](#contribution-guidelines)
  - [Developer Notes](#developer-notes)
  - [Links](#links)
  - [Testing](#testing)
  - [FAQs](#faqs)
  - [License](#license)
  - [Credits](#credits)
  - [Changelog](#changelog)
  - [Roadmap](#roadmap)

## Introduction

Our mobile app allows you to scan items in your pantry and suggest recipes based on the ingredients scanned. Based on the suggestions, you can also vote with your family and friends what you all want for dinner!

This project is divided into 3 parts: mobile, server, and website. This repo, mobile, has the code of our mobile app. The server repo is the one that contacts Spoonacular API. The website repo allows people to vote for people's favorite recipe.

We hope that you have fun and enjoy our app!

## Key Features

    + Item Quikshot - Add items on your pantry through your camera or text.
    + Recipe Finder - suggest recipes based on the items on your pantry.
    + Recipe Selector - Vote for the best recipe for your next meal. The app can add more voting participants.
    + Data Storage - Create an account and store your favorite recipes.
    + Mobile Cross Platform - Works with Android and iOS.

## Installation

1. Install Expo CLI - https://expo.dev
2. Git clone https://github.com/jaredhud/QuikDine-mobile.git
3. Git clone https://github.com/jaredhud/Quikdine-server.git
4. Git clone https://github.com/Kshitija118/QuikDineWebPage.git
5. npm install all the repos above
6. npm run start all the repos above

## Usage

## Examples
## Technologies Used

    + Core: React Native - React
    + API: Spoonacular Google Vision API
    + SendGrid Node.js Javascript HTML CSS Firebase Express.js Expo Go
    + Collaboration: Discord Github Zoom Trello Basecamp Figma

## Contributors List

- Romell Bermundo - [GitHub](https://github.com/steakncheese) - [LinkedIn](https://www.linkedin.com/in/romellbermundo/)

## Contribution Guidelines

- Fork the repository and clone it to your local machine.
- Create a new branch for your contribution.
- Commit your changes with clear messages.
- Push your branch to your forked repository.
- Open a pull request (PR) against the main repository's master branch.
- Participate in the PR review process.
- Once approved, your changes will be merged into the main repository.

## Developer Notes

- Context is used to transfer data from page to page
- Firebase is used to store data
- SendGrid is used for handling email functionality
- Navigation is handled 2 ways: Screen and Tab navigation
- \_RecipeNav and similar folders handles the Tab Navigation part
- Modal is used to create pop-ups (useful for creating help notes)
- When creating page layout, use percentages to divide sections. ie. 10% 10% 30%

<strong>Important</strong>: Add this code on src/context/ folder and name it as IPAddress.js:

    import { useState } from "react";
     
    export function setIP() {
    // your IP address, ipconfig in command prompt
    const [serverIP, setServerIP] = useState("Your IP address here");
    return { serverIP, setServerIP };
    }

## Links

[Documentation](https://github.com/steakncheese)
[Wiki](https://github.com/steakncheese)

## Testing
## FAQs

## License

The Aimeos TYPO3 extension is licensed under the terms of the GPL Open Source license and is available for free.
## Credits

+ [Node.js](https://nodejs.org/)
+ Base logo vector made by [Freepik](https://www.freepik.com/) from [Flaticon](www.flaticon.com).

## Changelog

## Roadmap
