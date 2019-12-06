# The MVC pattern

The Model View Controller design for web applications allows a project to conform to separation of concerns and single responsibiltiy principle

**Model(M):** 
- Contains all of the applications data
- Has the ability to manipulate the data
- Communicates with the controller, not the view

**View(V)** 
- Contains everything that the user will see (in the browser)
- Usually in the form of HTML, CSS and javascript
- Has no direct interaction with the model, any data it needs from the model to render the view will be via the controller

**Controller(C)**
- Receives requests from the user (browser)
- Contacts the model for any information it needs
- Sends the correct (updated view) back to the user (browser)


In summary

1. MVC stands for Model, View and Controller.
2. Model is responsible for maintaining application data and business logic.
3. View is a user interface of the application, which displays the data.
4. Controller handles user's requests and renders appropriate View with Model data.


![MVC Diagram](https://github.com/ajbacon/Portfolio/blob/master/images/mvc_diagram.jpeg)
