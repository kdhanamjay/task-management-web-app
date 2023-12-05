"# task-management-web-app" 

About the Task Management Web App:

TaskMaster is a robust full-stack task management application that allows users to efficiently create, update, and delete tasks. The application provides a seamless and intuitive user experience with features like task filtering, smooth interactions, and a responsive design. Built using modern front-end technologies.This is a responsive web app built with React & Redux.

**The challenge**
               **Users should be able to:**
 + View the optimal layout for the app depending on their device's screen size
 + See hover states for all interactive elements on the page
 + Create, read, update, and delete boards and tasks
 + Receive form validations when trying to create/edit boards and tasks
 + Mark subtasks as complete and move tasks between columns
 + Hide/show the board sidebar


**Expected Behaviour:**
       
  ** Boards**
  
+ Different boards can be selected by clicking on their respective links in the sidebar.
+ Selecting 'Create New Board' in the sidebar opens the 'Add New Board' modal.
+ Selecting 'Edit Board' from the dropdown menu triggers the 'Edit Board' modal, allowing changes to details.
+ Columns are added and removed for the Add/Edit Board modals.
+ Deleting a board deletes all columns and tasks and requires confirmation.

   **Columns**
  
+ Before tasks can be added, a board must have at least one column. If no columns exist, the "Add New Task" button in the header is disabled.
+ Selecting 'Add New Column' in the board settings opens the 'Edit Board' modal, enabling the addition of columns.

  **Tasks**
  
+ Assigning a new task places it at the bottom of the relevant column.
+ Changing a task's status moves it to the appropriate column.

   **Bonus:**
  
+ Tasks can be moved between columns by dragging and dropping them.


**Built with**

Semantic HTML5 markup

CSS

Flexbox

Mobile-first workflow

Drag and Drop API

React - JS library

Redux - State management tool
