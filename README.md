# Text_editor
A text editor which uses progressive web applications (PWA)


## 19 Progressive Web Applications (PWA) : Text Editor

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description

The application is a web text editor where the user can create notes or code snippets with or without an internet connection and where the user can reliably retrieve them for later use.  

This application is a Text Editor which uses PWAs allowing the user to create notes or code snippets either online or offline  (without the use of internet). The user can also install this application either with the insall button or by accessing the URL installation to have the application on their local machine. 

The URL of the GitHub repository is https://github.com/unfazedxx/Text_editor

🚀The application has been deployed to Render and the URL of the deployed application is:
 
https://mighty-waters-80466.herokuapp.com/

## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Technologies](#technologies)
* [Screenshots](#screenshots)
* [License](#license)

## Installation

*  To install this applicaiton please follow these directions:

    - Clone the github repository
    - Open the CLI in the Develop folder
    - (npm i) to install the required dependencies
    - (npm start) to start the application
        

## Usage

### User Story
```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

### Acceptance Criteria 
```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```


## Technologies
- Webpack & Workbox
- Concurrently
- JavaScript
- IndexedDB
- Express
- NodeJS
- Babel

## Screenshots

- This screenshot shows the deployed application right after running (npm start). See in the URL bar where we can install the applicatiion via PWA
![LocalHost3000 screenshot](image.png)

- This next screenshot shows the Service Workers working
![Registered SW](image-1.png)

- This shows the application working offline 
![Offline SW](image-2.png)

- This shows the IndexedDB 
![IndexedDB](<Screenshot 2024-01-29 at 7.45.18 PM.png>)

 
## License
This project is licensed under the terms of the MIT license.

## Author

I hope you enjoyed this walkthrough on the Text Editor using PWA's.

If you have further questions or wish to see the other projects I have completed, please visit my Github repository here: [Kunal's Github](https://github.com/unfazedxx).

You can also reach out via email at: 
<a href="mailto:shahkun01@gmail.com">shahkun01@gmail.com</a>

Happy coding 😊
