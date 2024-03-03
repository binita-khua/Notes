# Note Taker

## Description
Note Taker is an application that allows users to write, save, and delete notes. It uses an Express.js back end and saves and retrieves note data from a JSON file.

## User Story
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete

## Acceptance Criteria
GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
WHEN I enter a new note title and the note’s text
THEN a "Save Note" button and a "Clear Form" button appear in the navigation at the top of the page
WHEN I click on the Save button
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes and the buttons in the navigation disappear
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column and a "New Note" button appears in the navigation
WHEN I click on the "New Note" button in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column and the button disappears

## Installation
To install the application, follow these steps:
1. Clone the repository to your local machine.
2. Navigate to the root directory of the application in your terminal.
3. Run `npm install` to install all dependencies.
4. To start the server, run `node server.js`.
5. Navigate to `http://localhost:3000` in your browser to open the application.

## Usage
After opening the application in the browser:
- Click on 'Get Started' to go to the notes page.
- To create a note, enter a title and the note's text. Click 'Save Note' to save your note.
- Click on an existing note to view its content.
- Click 'New Note' to start a new note.

## Contributing
If you would like to contribute to this project, please follow the [Contributor Covenant](https://www.contributor-covenant.org/) standard.
