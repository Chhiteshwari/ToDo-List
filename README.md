## To-Do List App - HTML, CSS, and JavaScript

This repository contains the code for a simple yet functional To-Do List application built using HTML, CSS, and JavaScript. The app allows users to:

- Add new tasks
- Mark tasks as completed
- Delete individual tasks
- Delete all tasks
- Filter tasks by "Completed" or "Incomplete" status

**Features Used:**

**HTML:**
- Basic HTML structure for the app
- `<ul>` and `<li>` elements to create the task list
- `<input>` for user input
- `<button>` elements for adding, deleting, and filtering tasks
- Semantic HTML elements for better accessibility (e.g., `<h1>`, `<label>`)

**CSS:**
- Styling for the app's layout
- Basic styling of elements (e.g., input fields, buttons, list items)
- Hover effects for buttons and list items
- Responsive design using media queries for different screen sizes
- Background animation using CSS to give a cool and appealing look

**JavaScript:**
- DOM manipulation to add, remove, and update tasks dynamically
- Event listeners for user interactions (e.g., button clicks, input changes)
- Local storage to persist the To-Do list data even after the page is refreshed
- Functions to handle task addition, deletion, completion, and filtering
- Functionality to display a placeholder message when the list is empty

**Functionality Breakdown:**

1. **Add a Task:**
   - Users enter a task in the input field.
   - Pressing Enter or clicking the "+" button adds the task to the list.
   - The task is added to the beginning of the list with "pending" status.

2. **Mark a Task as Complete:**
   - Clicking the checkbox next to a task marks it as completed.
   - The task's status is updated in local storage.
   - The task gets a visual strikethrough effect.

3. **Delete a Task:**
   - Clicking the "delete" icon next to a task removes it from the list.
   - The task is removed from the list in local storage.

4. **Delete All Tasks:**
   - Clicking the "Delete All" button clears the entire To-Do list.
   - All tasks are removed from local storage.

5. **Filter Tasks:**
   - Clicking the "Completed" or "Incomplete" filter buttons displays only the respective tasks.
   - The filter remains active until another filter is clicked.

**How to Use:**

1. **Clone** this repository to your local machine.
2. **Open** the `index.html` file in your web browser.
3. **Start adding** tasks and enjoy the To-Do list app!

**Customization:**

- You can easily modify the CSS file to adjust the app's colors, fonts, layout, and styling.
- Feel free to add new features or modify the existing functionality to fit your needs.

Let me know if you have any questions!
