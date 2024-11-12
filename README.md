
# Kanban Board App

A simple and interactive Kanban board built with HTML, CSS, and JavaScript (DOM manipulation). This application allows you to create, edit, delete, and filter tasks based on category colors. Each task is locked by default, with unlock and color-changing functionalities for easy task management.

## Features

1. **Create Tasks**:  
   Add new tasks to the board. Each task is automatically assigned a unique ID.

2. **Four Color Categories**:  
   Tasks can be categorized with one of four colors:
   - **Red**: `#750E21`
   - **Blue**: `#213555`
   - **Green**: `#163020`
   - **Light Pink**: `#E9D5DA`

3. **Lock/Unlock Tasks**:  
   By default, tasks are locked to prevent accidental editing. You can unlock a task by clicking the lock icon, allowing you to edit task content or switch its color category.

4. **Change Task Category**:  
   Once unlocked, you can change a task's category by clicking the color indicator on the task card.

5. **Delete Tasks**:  
   - To enable delete mode, click the delete icon, which changes color.
   - While in delete mode, click any task(s) you want to delete.
   - To exit delete mode, click the delete icon again to revert its color.

6. **Filter Tasks by Category**:  
   Filter tasks based on their color category to focus on specific groups.

## Installation

No installation is required; simply open the `index.html` file in a browser.

## Usage

1. **Adding a Task**:
   - Use the task creation input (or button, as applicable) to add a new task.
   - Choose the color category for the task as needed.

2. **Editing a Task**:
   - Click the lock icon to unlock a task for editing.
   - Once unlocked, edit the content and change the color category as desired.

3. **Deleting a Task**:
   - Enter delete mode by clicking the delete icon.
   - Click on tasks to delete them.
   - Exit delete mode by clicking the delete icon again.

4. **Filtering Tasks**:
   - Use the color filters to view tasks in a specific category.

## Technologies Used

- **HTML**
- **CSS**
- **JavaScript (DOM Manipulation)**

## License

This project is open-source and available for use under the [MIT License](LICENCE.md).
