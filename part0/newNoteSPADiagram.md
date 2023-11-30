sequenceDiagram
	participant browser
	participant server

	browser->>Server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
	activate server

	Note right of browser: JavaScript send note to the server and then renders all notes. 
