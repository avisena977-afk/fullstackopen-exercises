```mermaid
sequenceDiagram
participant browser
participant server
Note right of browser: The browser adds the note to the list and rerenders the UI
browser-->>server: POST http://helsinki.fi
activate server
server-->>browser: 201 Created

deactivate server
```
