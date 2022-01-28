# To-do API
 Rest API built in order to put into practice the knowledge about HTTPs methods, the main return codes and types of parameters of a request.
 
 This is a challeng proposed by RocketSeat in a NodeJs teaching trail: https://app.rocketseat.com.br/ignite

### App Routes:

```POST/users```

```GET/todos```

```POST/todos```

```PUT/todos/:id```

```PATCH/todos/:id/done```

```DELETE/todos/:id```

### Unit tests

- Should be able to create a new user
- Should not be able to create a new user when username already exists

### To-do tests

- Should be able to list all user's todos
- Should be able to create a new todo
- Should be able to update a todo
- Should not be able to update a non existing todo
- Should be able to mark a todo as done
- Should be able to delete a todo
- Should not be able to delete a non existing todo
