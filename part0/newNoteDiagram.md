sequenceDiagram
	participant browser
	participant server

	browser->>server: HTTP POST https://studies.cs.helsinki.fi/exampleapp/new_note
	activate server
	server-->>browser:  https://studies.cs.helsinki.fi/exampleapp/notes
	desactivate server