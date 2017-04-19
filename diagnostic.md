# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```md
this is where all the data is stored to and accessed from
```

Which layer in the MVC pattern is used by the controller to fetch data?

```md
model
```

Which layer in the MVC pattern communicates with the model?

```md
controller
```

Why don't we use views in our interpretation of the MVC pattern?

```md
we had already done that with the html, css, and javascript
```

What does C.R.U.D stand for?

```md
Create
Read
Update
Delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```md
controller
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```md
index, show, create, update, destroy
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```md
1. the router issues a request to the controller for /people/1
2. the controller issues a request to the model for get data for /people/1
3. model tries to find the data associated for GET /people/1 and returns a response
4. the controller recieves the response from the model and sends the response message to the viewer
```

What is the command to generate a new rails-api app?

```bash
bin/rails generate controller new-app-name
```

What is the command to start an instance of a rails server?

```bash
bin/rails server
```

What are the commands to drop, create, migrate and seed a database from the command
line? (5 bullet points)

```bash
bin/rails generate migration 
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
// your response here
```
