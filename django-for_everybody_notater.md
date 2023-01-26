# Notater til Django for Everybody

## Browser Debugger Console

**Konsollen i browseren din, det du bruker for å debugge nettsidene din, lar deg se DOM.**

### Request response cycle:

- Browser makes connection.
- Sends get request to webserver with desired URL.
- Webserver sends back a response, 200 or 404.
- Browser sends a set of headers with more information.
- Gets back the data it asked for, parses the data and creates the DOM.
- You can now edit the DOM manually or with Javascript without server involvement.

---
## The Structure of a Django Application

### What is a Django application?
- A django project is a collection of applications, you can use one application in multiple projects.
- You change Djangos behavior by definings objects and registering those objects.
- Routing step picks what part of your application to run the GET request too.
- View will recieve the request and potentially store data, and then the view finishes and sends something back.

### What happens when a user clicks: 
- Users clicks something on the Website.
- Browser and Webserver create a socket connection and sends request.
- The request goes to urls.py, urls.py decides which views to run. 
- If we need to store data we call the model.
- All the data we need is combined into a response which is formatted by Templates and sent back.

### The Three Functions:
- Routing
- Views
- Models

---
## Begreper

| Begrep | Forklaring |
| ------ | ---------- |
| Django | Way to build web applications |
| DOM | Document Object Model |
| HTML | Hypertext Markup Language |
| Model.py | Informs how we store data in the database |
| Request response cycle | Fram og tilbake kommunikasjonen mellom nettleseren og webserveren |
| GET request | Nettleseren spør Webesereren om å hente ut data utifra spesifikasjoner i requesten |


