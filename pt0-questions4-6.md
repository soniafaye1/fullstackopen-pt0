# fullstackopen-pt0
<h3>0.4: New note diagram</h3>
Create a similar diagram depicting the situation where the user creates a new note on the page https://studies.cs.helsinki.fi/exampleapp/notes by writing something into the text field and clicking the Save button. 

<br>Browser --> POST https://studies.cs.helsinki.fi/exampleapp/notes --> Server <br>
Browser <--                  notes html file                    <-- Server

Browser --> Get https://studies.cs.helsinki.fi/exampleapp/main.css --> Server <br>
Browser <--                        css file                        <-- Server

Browser --> Get https://studies.cs.helsinki.fi/exampleapp/main.js --> Server <br>
Browser <--                   JavaScript file                     <-- Server

Browser --> Get https://studies.cs.helsinki.fi/exampleapp/data.json --> Server <br>
Browser <--               json file with content of all notes                     <-- Server

<h3>0.5: Single page app diagram</h3>
Create a diagram depicting the situation where the user goes to the single-page app version of the notes app at https://studies.cs.helsinki.fi/exampleapp/spa. 

<br>Browser --> Get https://studies.cs.helsinki.fi/exampleapp/spa --> Server <br>
Browser <--                  spa html file                    <-- Server

Browser --> Get https://studies.cs.helsinki.fi/exampleapp/main.css --> Server <br>
Browser <--                        css file                        <-- Server

Browser --> Get https://studies.cs.helsinki.fi/exampleapp/spa.js --> Server <br>
Browser <--                   JavaScript file                     <-- Server

Browser --> Get https://studies.cs.helsinki.fi/exampleapp/data.json --> Server <br>
Browser <--                json file with content of all notes                     <-- Server

<h3>0.6: New note in Single page app diagram</h3>
Create a diagram depicting the situation where the user creates a new note using the single-page version of the app. 

<br>Browser -->    POST https://studies.cs.helsinki.fi/exampleapp/spa   --> Server <br>
Browser <--  new_note_spa json file <-- Server
