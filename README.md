# CODTECH-Task2
Name: VEETHISH KRISSHNA 
Company:CODTECH IT SOLUTIONS
ID:CT12DS3060
Domain: Software Development 
Duration: Dec 12th to Feb 12th 2025
Mentor:NEHA


# OVERVIEW OF PROJECT 
This is a simple Task Manager web application built using HTML and JavaScript, without the use of external or internal CSS for styling. It serves as a basic tool to allow users to add, toggle, and visually mark tasks as completed.

Key Features:
Task Creation:

Users can add new tasks by typing in an input field and clicking an "Add" button.
The tasks are displayed in a list, and each task includes a checkbox next to it.
Task Completion:

Users can mark a task as "completed" by clicking on the checkbox.
Once checked, the task's text gets a line-through effect (indicating completion), and the text color changes to gray.
If the checkbox is unchecked, the task returns to its normal state, with no line-through and black text.
Simple Design:

The layout is very basic, relying on the default browser styles, with no advanced design or layout.
The interactivity of the tasks is controlled by JavaScript, which modifies the task's appearance dynamically.
Technical Components:
HTML (Structure):

The HTML defines the structure of the page, including:
A header with the title of the application.
An input field for entering new tasks.
A button to add tasks to the list.
A section to display the task list.
JavaScript (Functionality):

addTask(): Handles adding a new task to the list. It checks if the input is non-empty, creates a new task element, and appends it to the task list.
toggleTask(): This function is triggered when a task's checkbox is clicked. It toggles the task's completion state, applying a line-through style and changing the text color for completed tasks.
Inline Styling via JavaScript:

Rather than using CSS, styling is done programmatically within JavaScript. When a task is marked as completed, the task's text decoration (line-through) and color are modified directly using JavaScript.
Project Workflow:
Adding a Task:
When the user types a task and clicks the "Add" button, a new task is created and added to the task list.
Each task contains a checkbox, and the task text is added to a <div> element.
Marking a Task as Completed:
When the user clicks the checkbox, the toggleTask() function is triggered.
The task's text is visually crossed out, and its color changes to gray to indicate it's completed.
Removing Task Styling:
When the checkbox is unchecked, the line-through effect and gray color are removed, restoring the task to its original state.
Strengths:
Simplicity: The application is very simple, making it easy to understand and modify.
No External Dependencies: There is no reliance on CSS or external libraries, making it lightweight.
Basic Functionality: It provides essential task management features (adding tasks and marking them as completed).
Potential Limitations:
Design and User Experience: Without CSS, the design is very basic, and it lacks a polished or user-friendly interface.
No Task Deletion or Editing: The application currently lacks features like deleting or editing tasks after they are created.
No Persistence: Tasks are lost if the page is refreshed, as there is no storage solution (e.g., localStorage or a database) implemented.
Potential Improvements:
Task Deletion: Implement a delete button next to each task, allowing users to remove completed or unwanted tasks.
Persistent Storage: Use localStorage or sessionStorage to save tasks so that they persist across page reloads.
Styling: Introduce basic CSS to improve the visual design, making the application more user-friendly.
Task Editing: Allow users to edit a task after it has been added.
Enhanced Features: Implement features like task categorization, prioritization, or due dates.
Accessibility: Add ARIA attributes and improve keyboard navigation for users who rely on screen readers or other assistive technologies.


Conclusion:
This Task Manager (without CSS) is a basic and lightweight web application demonstrating core functionalities like task creation, toggling task completion, and basic DOM manipulation. It is a good starting point for beginners to practice using HTML and JavaScript together. However, for a fully featured task management tool, additional features like CSS styling, task persistence, and more advanced functionality could be added in the future.






