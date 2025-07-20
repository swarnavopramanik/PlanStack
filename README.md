# Shows planning and stacking tasks for completion.



<img width="1906" height="962" alt="image" src="https://github.com/user-attachments/assets/fc8d975d-460d-495d-8b0e-85eda65f4a80" />


# The application should offer three distinct ways to group the data:
- By Status: Group tickets based on their current status.
- By User: Arrange tickets according to the assigned user.
- By Priority: Group tickets based on their priority level.
# Users should also be able to sort the displayed tickets in two ways:
- Priority: Arrange tickets in descending order of priority.
- Title: Sort tickets in ascending order based on their title.

# The priority levels for the tickets are as follows:
- Urgent (Priority level 4)
- High (Priority level 3)
- Medium (Priority level 2)
- Low (Priority level 1)
- No priority (Priority level 0)
- Priority levels: (This values you will receive in the api)
  
4 - Urgent
3 - High
2 - Medium
1 - Low
0 - No priority


# Recommended Libraries:
* Use NextJS + React / Vite + React , Tailwind, Zustand / ContextAPI etc.
Evaluation Criteria
# Evaluated based on the following criteria:
- Functionality: The application should effectively fetch data from the provided API and allow users to group and sort tickets based on the given options.
- Visual Design: The UI should match the provided design, including the layout, card design, and overall aesthetics.
- Business Logic Optimisation
- Component Structuring: Components should be appropriately structured, promoting reusability and maintainability.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Built with](#built-with)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the app depending on their device's screen size
- See hover states for all interactive elements on the page
- Create, read, update, and delete boards and tasks
- Receive form validations when trying to create/edit boards and tasks
- Mark subtasks as complete and move tasks between columns
- Hide/show the board sidebar

Expected Behaviour:

- Boards
  - Clicking different boards in the sidebar will change to the selected board.
  - Clicking "Create New Board" in the sidebar opens the "Add New Board" modal.
  - Clicking in the dropdown menu "Edit Board" opens up the "Edit Board" modal where details can be changed.
  - Columns are added and removed for the Add/Edit Board modals.
  - Deleting a board deletes all columns and tasks and requires confirmation.

- Columns
  - A board needs at least one column before tasks can be added. If no columns exist, the "Add New Task" button in the header is disabled.
  - Clicking "Add New Column" opens the "Edit Board" modal where columns are added.
- Tasks
  - Adding a new task adds it to the bottom of the relevant column.
  - Updating a task's status will move the task to the relevant column.

### Bonus:

- The tasks can be dragged and dropped to a new column.

  ### Screenshot

![Screenshot (633)](https://github.com/swarnavopramanik/Kanban-application/assets/105142693/5235d261-3157-412b-8468-6641753fc6f2)
![Screenshot (635)](https://github.com/swarnavopramanik/Kanban-application/assets/105142693/5630ee65-a4bc-44ca-912a-4dfbea67ba25)


### Links [Video]
[Frontend assignment.webm](https://github.com/swarnavopramanik/Kanban-application/assets/105142693/3430d366-4657-428a-a518-84b6ca5e7a2b)

- Live Site URL: [link](https://kanban-application-ten.vercel.app/)

  # Built with

- [TailwindCSS](https://tailwindcss.com/) - CSS Framework
- Drag and Drop API
- [React](https://reactjs.org/) - JS library
- [Redux](https://redux.js.org/) - State management tool



