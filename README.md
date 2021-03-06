#Node Express jQuery Code Challenge

This project was meant to exercise our use of logic on both the client and the server.

---

### Objectives
- Initialize and spin up a server side node/express application.
- Send requests to the server from both the browser and using ajax in the client side script.
- Display response on the DOM.
- Demonstrate the separation of logic between the client and the server.

### The Joke Book

Your client has asked you to create a Joke Book application. The server will contain all the current joke data and you have been provided with the initial server file (```server/app.js```).

Your job will be to build up the server around the data in the ```server/app.js``` file, display the current jokes to the DOM, and add the ability for users to add their own jokes and display these too.

#####How the joke data is structured
You can view the full object in ```server/app.js```. The data structure is an array of objects. These objects have three properties: whoseJoke, jokeQuestion, and punchLine.

```
jokes = [
  {
    whoseJoke: "Huck",
    jokeQuestion: "What's the difference between roast beef and pea soup?",
    punchLine: "Anyone can roast beef."
  }]
```

To get started, fork this repo and clone it to your machine.

### Reminder

Focus on getting the app up and running first. You can come back and clean things up later if you have time.
