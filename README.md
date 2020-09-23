# ECE444-F2020-Lab2
Name: Yudong (William) Xu

This repo is a clone of https://github.com/miguelgrinberg/flasky

## Task 1
![Screenshot](task1.png)


## Task 2
![Screenshot](task2.png)


## Task 3
For a view function to handle a user request, it needs to have access to a few objects such as the *request* object which 
encapsulates the HTTP request sent by the client. Flask context globals allow these variables to become
globally accessible without interfering with other threads, and without having to pass the variables as arguments to the functions.

There are 2 contexts in Flask: *application context* and *request context*

There are 4 Flask context globals:
- current_app(application context): The application instance for the active application
- g(application context): an object for temporary storage for the application
- request(request context): encapsulates the HTTP request sent by the client
- session(request context): a dictionary the application can use to store values