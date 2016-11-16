# Rails API Diagnostic

Place your responses inside the fenced code-blocks where indicated by comments.

What is the purpose of a backend?

```bash
The backend enables you to store, manage, and retrieve the data related to your
project/site/business, etc.
```

Which layer in the MVC pattern is used by the controller to fetch data?

```bash
The controller uses the model to fetch data.
```

Which layer in the MVC pattern communicates with the model?

```bash
The model fetches data from the model which returns that to the controller.
```

Why don't we use views in our interpretation of the MVC pattern?

```bash
Because our view logic will be contained in html and js
```

What does C.R.U.D stand for?

```bash
Create, Read, Update, Delete
```

In which part of the MVC pattern can we find C.R.U.D actions?

```bash
In the controller.
```

List at least 5 standard rails actions that C.R.U.D requests correspond to?

```bash
Index, Show, Create, Update, Destroy
```

A user action fires a `GET` request for `/people/1`. Explain in detail each step
required for data to be returned to the client. (bullet points or ordered list)

```bash
1. Request arrives at Web server from client
2. Router passes request to appropriate 'people' controller
3. Controller communicates with the appropriate 'people' model
4. The requested data is retrieved from the DB and returned to the 'people'controller
5. The 'people' controller returns the request to the client
```

What is the command to generate a new rails-api app?

```bash
bundle install
```

What is the command to start an instance of a rails server?

```bash
bundle exec rails server
```

What are the commands to drop, create and migrate a database from the command
line? (3 bullet points)

```bash
 - bundle exec rake db:drop
 - bundle exec rake db:create
 - bundle exec rake db:migrate
```

What is the command to scaffold a pet with a name and age attributes (hint:
Also think of the data types for each attribute)?

```bash
rails g scaffold pet name:string age:integer

```
