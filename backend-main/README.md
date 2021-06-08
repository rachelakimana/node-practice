# Awesomity Backend Challenge

Create a To-Do API. The To-Do API should allow the following operations on a todo item:

Create, Update, Read, Delete

### 🏗Object/Modal Structure

A todo item is made of:

- Title
- Description
- Priority (LOW, MEDIUM, HIGH)
- CreateDate (date of creation of the todo item)
- ModifiedDate (date of modification of the todo item)

### 🔖Requirements

- Someone can create / update a todo item by sending:
    - title
    - description
    - priority

    The date of creation should be time stamped automatically when created

- Someone can read one or many todo items
- Someone can delete a todo item
- Your project should be on an online repository (Gitlab, Github,...)

### 📝Submission
- Send us your submission as an email to team@awesomity.rw.
- The subject of the email should be `Task Force Challenge-{NAME_OF_THE_CHALLENGE}` eg: Task Force Challenge-Frontend
- The content of the email should have your full names, personal phone number as well as the git repo link of the challenge
- Deadline: 24th Feb at noon, submit before then

### 👷🏽‍♀️Best Practices

- Document your methods. Tip: [JSDoc](https://jsdoc.app/), [Javadoc](https://docs.oracle.com/javase/7/docs/technotes/tools/windows/javadoc.html)
- Write tests with a minimum of 60% coverage
- Document your API  ([Swagger](https://swagger.io/))
- Validate your request bodies
- Properly log your application
- Have a Dockerized environment(`Dockerfile`, `docker-compose.yml`)
- Write a good README file with the steps to Install & run your application (steps for docker included)

### ✨Bonus

- Add User authentication
- Add Search & Export to CSV on TODO items
