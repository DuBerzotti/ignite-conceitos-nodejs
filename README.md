
### How to use

#### Create user

**Method:<font color="green"> Post </font>**

 + Url
     + /users

To create a user it is necessary to send the information by body:

    {
    "name": "User name",
    "username": "user.name"
    }

#### Create task

**Method:<font color="green"> Post </font>**

 + Url
     + /todos

To create it is necessary to send the information by body:

    {
    "title": "Title",
    "deadline": "AAAA-MM-DD"
    }

And that information by Header:
 + username
     + User name created
 + deadline
     + AAAA-MM-DD

#### Get task

**Method:<font color="blue"> Get </font>**

 + Url
     + /todos

To get the list it is necessary to send the information by Header:

 + username
     + User name created

#### Update task by ID

**Method:<font color="ff8c00"> Put </font>**

 + Url
     + /todos/:id

To update it is necessary to send the information by body:

    {
    "title": "New Title",
    "deadline": "AAAA-MM-DD"
    }

And that information by Header:
 + username
     + User name created

#### End task

**Method:<font color="ffd700"> Patch</font>**

 + Url
     + /todos/:id/done

It is necessary to send the task ID by parameter in the url:

> /todos/:id/done

And that information by Header:
 + username
     + User name created

#### Delete Task

**Method:<font color="ff0000"> Delete </font>**

 + Url
     + /todos/:id/

To delete is necessary to send the information by Header:

 + username
     + User name created

And it is necessary to send the task ID by parameter in the url:

> /todos/:id
