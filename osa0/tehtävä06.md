```mermaid

sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/spa/new_note_spa

    Note right of browser: The browser sends note data to the server as content

    activate server
    server->>browser: 201 created
    deactivate server
    


```