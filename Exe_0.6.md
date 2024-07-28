```mermaid

sequenceDiagram


    
    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    activate server

    server-->>browser: See al the new information in the HTML.
    deactivate server
    

    Note right of browser: We stay in teh same page and the information actualice the HTML fILE.