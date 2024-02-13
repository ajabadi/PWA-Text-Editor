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

4. Loading the web application should have a registered service worker using workbox
   Then registering a service worker should display static assets pre cached upon loading along with subsequent pages and static assets
<img width="1292" alt="Screen Shot 2024-02-12 at 21 29 02" src="https://github.com/ajabadi/PWA-Text-Editor/assets/145517793/a9b1841a-40fa-4609-9e03-a635d5850883">
<img width="1308" alt="Screen Shot 2024-02-12 at 21 35 09" src="https://github.com/ajabadi/PWA-Text-Editor/assets/145517793/4138fc1f-ab00-4ac2-b14a-8a130c711685">

5. The web application is [deploy](https://text-editor-9gj3.onrender.com) to Render, it should have proper build scripts for a webpack application
   ![Screen Shot 2024-02-12 at 19 39 29 (2)](https://github.com/ajabadi/PWA-Text-Editor/assets/145517793/4480cdae-e20b-4bef-ae80-3324b688cba9)
