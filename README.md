<img width="1285" alt="Screen Shot 2024-02-12 at 19 43 08" src="https://github.com/ajabadi/PWA-Text-Editor/assets/145517793/d90b5633-c7cb-4fcc-9a72-d5b7a48248e4"># PWA Text Editor

## Description

The PWA Text Editor is a sophisticated, single-page application that functions both online and offline, meeting all the PWA criteria. This application is designed to offer developers the ability to create and save notes or code snippets with the convenience of persistent data storage through IndexedDB, making it possible to retrieve them at any point, with or without an internet connection. Built upon an existing application, this project incorporates the idb package—a lightweight IndexedDB API wrapper employed by giants like Google and Mozilla.

## User Story
As a developer,I want to create notes or code snippets with or without an internet connection to retrieve them for later use.

## Technologies Used
- Node.js
- Express.js
- Webpack
- Babel
- CSS-loader
- IndexedDB
- Concurrently

## Usage

 1. Run `npm run start` from the root directory
    The application should start up the backend and serve the client
    Run the text editor application from my terminal, the JavaScript files will be bundled using webpack
    Run my webpack plugins will generate HTML file, service worker, and a manifest file
    <img width="1285" alt="Screen Shot 2024-02-12 at 19 43 08" src="https://github.com/ajabadi/PWA-Text-Editor/assets/145517793/17dfaf9c-ec8a-4787-9cfd-1c2ef4fe05f9">

2. Then the IndexedDB has immediately created a database storage
   Enter content and subsequently click off of the DOM window, the text editor has been saved with IndexedDB
   Reopening the text editor after closing it, the content in the text editor has been retrieved from our IndexedDB
![Screen Shot 2024-02-12 at 21 00 44](https://github.com/ajabadi/PWA-Text-Editor/assets/145517793/5a7c271d-8bd4-42eb-bfc8-55a8f8008d79)


3. Clicking on the Install button,the web application will be downloaded as an icon on my desktop
<img width="571" alt="Screen Shot 2024-02-12 at 21 38 56" src="https://github.com/ajabadi/PWA-Text-Editor/assets/145517793/58963eb1-749e-41cc-ae15-967df903af51">

4. 
