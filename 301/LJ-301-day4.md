Trying out a different style of this today. Actually going to use it as my class notes, so we will see how this goes with a summary entry like all previous LJs at the end of the notes.

**MVC - Model View Controller**
* View: front-end, client-side, what user sees. Presentation of page and interaction with page.
* Controller: communication between view + model (DOM), validation of input, updating view of page based on interaction, server.js
* Model: database (we use SQL, not the only one we have available, JS401 uses MongoDB Python401 uses SQL). Where we store info, persistance of storage and associated details. 

**WRRC Web Request Response Cycle**
Communication from view to controller is known as a **request (req)**, and the controller gives **response (res)** to the request from the view. If the controller doesn't have info requested, it makes a **query** to the model (database) which provides a **result** to the controller (server), which then responds to the view (user).

Server is a little funky, since it can be its own separate machine, can be referring to a single file on your machine (file telling front end what to do when it gets a request).


_1st break_


**HTTP Party**
Browser create a HTTP Request Object
HTTP Request has 3 parts:
1. URL (twitter.com)
2. Method (GET)
3. Headers 

The server:
* receives the request
* builds a response
* sends it back to the client

HTTP Response also has 3 parts:
1. Status code (200, 301, 404, 500, etc)
    * <https://en.wikipedia.org/wiki/List_of_HTTP_status_codes>
2. Headers (info about the server/file sent)
3. Body (content of page)
    * HTML, CSS, JavaScript

**JSON**
Standard way to _serialize_ objects.
* "Dehydration for data structures"
* Reconstitute it later when needed
Used instead of XML b/c:
* More human readable
* More "object-oriented"
* Lighter

