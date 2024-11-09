# Markdown Editor with Live preview
Markdown editor is a tool that allows users to write and preview text formatted with Markdown syntax, which is then converted into HTML.


## Technologies Used
- **Frontend**: React
- **Backend**: Express.js and Node.js
- **Markdown to HTML Conversion**: `marked` library

## Setup Instructions

Follow these steps to set up and run the Markdown App locally:

###  Clone the Repository
git clone https://github.com/your-username/markdown-app.git
cd Markdown-editor
cd backendServices
npm install
create a .env(in this project only PORT is maintained).
npm start 

For frontend setup
cd frontendServices
npm install
npm start    

## Open your browser and navigate to http://localhost:3000. You should see the Markdown Editor and HTML Preview areas.

## You can type markdown text in the Markdown Editor and it will automatically convert and display the HTML in the HTML Preview section.

## This might be a case you will face ne issue while running application that marked is not a function , so you just need to go backend folder open index.js and replace const { marked } = require('marked'); with const marked = require('marked');

## sample Input for testing - use hashtag and space in starting of all 
- # My **bold** heading
- # H1
- ## H2 # 