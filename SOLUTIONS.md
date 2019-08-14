### Rails MVC

First, start the rails server. Then, make a request to `/tasks/new`, fill out the form and submit it in order to create a new task.

1. What controller and action handles the data from the form submission?

task_controller ==> create action

2. What controller and action would be used if you did a `GET` request on the `/users` route?

user_controller --> index action

3. Write out the step-by-step process that your rails application will take to render the `tasks/new` route.

    a. User calls tasks/new
    b. router checks controller
    c. router finds view
    d. view is rendered

4. What file is responsible for managing the mapping between your application and the `tasks` database table?

    Tasks model

    



### Rails RESTful Actions

5. Explain all 7 of the RESTful actions in Rails

   - List each action by its name

   - Explain which HTTP verbs pair with each action

   - Write a short sentence for each action that summarizes what it does

    EXAMPLE: BOOKS

    index: displays a list of all books | GET
    new: HTML form for adding new BOOK | GET
    create: Creates a new book in DB | POST
    show: Shows a specific book from DB | GET
    edit: HTML form for editing existing book | GET
    update: Updates a specific book | PATCH / PUT
    destroy: Deletes a specific book | DELETE


User.create( :email => 'dude@dude.com', :active => true )

User.create( :email => 'nice@nice.com', :active => false )