# Note_Taker

## Description
This application allows users to create notes with titles, save them to a server, then either create more notes or refer back to previously saved ones.


## User Story

```
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
```


## Acceptance Criteria

```
GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
WHEN I enter a new note title and the note’s text
THEN a Save icon appears in the navigation at the top of the page
WHEN I click on the Save icon
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column
WHEN I click on the Write icon in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column
```


## Installation
Programs necessary for usage is Node.js and Express.js, but dependencies must be added for it to work.  Express must be installed into the node_modules folder using, "npm install 'program'".  Finally, this must be run using node or nodemon, as the server is hosted locally.


## Usage
After one opens the application, they will be greeted by a launch screen.  When they click, 'Get Started,' the application opens.  When someone clicks on Note Title, they can title the note, then click the Note Text to write their description.  When both text fields are populated, a save button appears, which when clicked, will save the note to the list on the left hand side of the page.  If the user clicks on the previous notes, the information will populate.  If they want to make another note, they can click the plus sign in the upper right hand corner.




## Screenshot
![Screenshot](./Assets/notetaker.png)


## Links
Site Link: Not applicable, as this assignment must be run from localhost:3001 
Github: https://github.com/mcalcagno47/Note_Taker  


## Credits
Mark Calcagno
Juan Santiago, tutor
Tucker from askBCS

## Future Development
I hope to return to the document to make the delete button function.  