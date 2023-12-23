# Kanban-board-application

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
  - [Useful resources](#useful-resources)


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

Bonus:

- The tasks can be dragged and dropped to a new column.

  ### Screenshot

[Screenshot (633)](https://github.com/swarnavopramanik/Kanban-application/assets/105142693/68e1c73d-3d29-4779-9fa0-13b8ad6cb07f)


