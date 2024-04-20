## Flask Application Design

### Problem Statement
Given a list of tasks for a day, a user should be able to add, remove, and mark tasks as completed through a web interface.

### HTML Files

- `index.html`: Main page of the application, displaying the list of tasks.
- `add.html`: Form for adding a new task.

### Routes

- `/`: GET request returning the `index.html` page.
- `/add`: POST request adding a new task to the list and redirecting to `/`.
- `/remove/<int:task_id>`: POST request removing the task with the specified ID.
- `/complete/<int:task_id>`: POST request marking the task with the specified ID as completed.