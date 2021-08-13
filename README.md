# js-assessment
## Vue Js assessment task

This code challenge is to assess your frontend skills in developing a simple todo list application. For this code challenge you must use VueJS 3. Please note that the code should be clean, commented and well structured.

You are free to use any css framework or UI library that you want. You can use our hosted api please import the collection of endpoints into postman using this url https://www.getpostman.com/collections/0bf6bd07034669df5654

There will be 6 screens in total: welcome screen (for guest users), login, register, ToDos list, create new ToDo, view/update ToDo

Once the user is logged in, they should stay logged in (even if the page is refreshed) using the existing token. Logout button in navigation which will logout the user. UI will not be a part of this assessment so please focus on the quality of the code.

### Welcome screen: 
- will only be visible if a user is not logged in and is on route '/'

### Register screen:
- Only 3 fields are required, email, password and password confirmation.
- Upon successful registration the user will be notified to check their email inbox and redirected to the login screen

### Login screen:
- 2 fields are required - email and password
- If credentials invalid show appropriate user feedback
- If credentials are correct the user should be logged in and redirected to '/' (which is now the list of my ToDos screen)

### ToDo list:
- The user should see a list of their previously created ToDos
- The user should be able to navigate to the "Create new ToDo"
- The user should be able to navigate to the "View/update ToDo" screen by clicking on one of the ToDos item from the list
- The user should be able to delete a particular ToDo item from the list
- ToDo items should be searchable by title
- Pagination should be handled as an infinite scroll

### Create ToDo screen:
- 2 fields are required, title and description
- Upon successfully creating the ToDo item the user should be redirected to the "ToDo list" screen

### View/update ToDo screen:
- 2 fields are required, title and description of the ToDo item, and these fields should be pre filled with data from the server for the selected ToDo item.
- Upon successfully updating the ToDo the user should be redirected to the "ToDo list" screen

