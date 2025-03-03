# ToDoList 

A simple and user-friendly To-Do List application to manage daily tasks efficiently.  
It allows users to add, edit, mark as completed, and delete tasks.

##  Features
-  Add new tasks  
-  Mark tasks as complete  
-  Delete tasks  
-  Edit existing tasks  
-  Simple and clean UI
  
1. User Interface
✔ Visually Appealing UI
•	The UI is simple and clean with a container, heading, input box, buttons, and a task list.
•	Uses CSS to style the layout effectively.
✔ Input Section for New Task
•	There is an input field <input type="text" id="taskInput"> where users can enter new tasks.
✔ Task Display with Checkboxes
•	Tasks are displayed in a list (<ul id="taskList">), and each task has a checkbox (<input type="checkbox">) to mark it as completed.
✔ Edit and Delete Options
•	Each task has:
o	Edit button (<button class="btn-edit" onclick="editTask(this)">Edit</button>)
o	Delete button (<button class="btn-delete" onclick="deleteTask(this)">Delete</button>)
________________________________________
2. Functionality
✔ Add New Tasks
•	Users can enter a task and click the "Add" button to add it to the list.
✔ Mark Task as Completed/Incomplete
•	Clicking the checkbox applies a line-through effect (.completed class) to mark the task as completed.
✔ Edit Tasks
•	Clicking the "Edit" button prompts the user to modify the task description.
✔ Delete Tasks
•	Clicking the "Delete" button removes the task from the list.
________________________________________
3. Validation
✔ Prevents Empty Tasks
•	If the user tries to add an empty task, an alert message ("Task cannot be empty!") is shown.
✔ Handles Potential Errors
•	If the user cancels the Edit task prompt, the original text remains unchanged.
________________________________________
4. Local Storage
✔ Stores Tasks in Browser Memory
•	saveTasks() function saves tasks in localStorage.
•	loadTasks() function loads saved tasks when the page refreshes.
•	Tasks remain even after refreshing or reopening the page.
________________________________________
5. Responsive Design
✔ Adapts to Different Screen Sizes
•	Uses CSS media queries (@media) to ensure proper display on smaller screens.
•	The .container width adjusts for mobile devices.

 

