# Progressive Web Application (PWA) Text Editor

## Description

A simple text editor with color-formatting and the option to install application locally.

Progressive Web Applications are difficult to wrap your head around initially, and this being my first go at making one work that was a doubley the case. Working with a new-to-me database in IndexedDB while managing multiple file structures was a challenge, but after the initial confusion it was relatively easy to comprehend and work with.

## Installation

This app is deployed on Heroku: [Click here!](https://fast-castle-52535-4f652263b357.herokuapp.com/)

If you prefer to deploy this app locally you'll need to do the following:

- Clone the repository to your local machine
- Navigate to the projcet repository
- Type `npm install` in the terminal to install dependencies in the root folder, client folder, and server folder
- Type `npm run start:dev` to build the webpack and run the app
- Navigate to http://localhost:3000 in your browser to view the app

## Usage

Using this webapp you can do the following:

- Write and edit code snippets with built-in basic color formatting.
- Save your data locally using IndexedDB by pressing 'enter' to move the cursor to the next line.
- Access this data even while offline thanks to IndexedDB.
- Install this application as a standalone app for use without having to navigate to the url in your browser.

![J.A.T.E. Demo Gif](/assets/images/README1.gif)

## Technologies

- [babel](https://www.npmjs.com/package/Babel) - Allows backwards compatible versions of JavaScript in older browsers.
- [webpack](https://www.npmjs.com/package/webpack) - Module bundler.
- [workbox](https://www.npmjs.com/package/workbox-webpack-plugin) - Plugin for webpack.
- [codemirror](https://codemirror.net/) - Code editor component for the web.
- [indexedDB](https://www.npmjs.com/search?q=IndexedDB) - API for client-side storage.