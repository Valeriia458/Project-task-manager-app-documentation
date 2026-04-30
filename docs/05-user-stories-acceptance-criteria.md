User Stories & Acceptance Criteria: TaskFlow App
Project: TaskFlow
Author: Valeriia, IT Project Manager
Status: Ready for Development
1. Core Task Management (The Essentials)
User Story #1: Create a Task
As a user, I want to quickly add a new task with a title and due date, so that I don’t forget what I need to do.
Acceptance Criteria:
The user can enter a task title (max 100 characters).


The user can select a due date from a calendar picker.


The system saves the task and displays it immediately in the list.


An error message appears if the title is left blank.


User Story #2: Filter by Priority
As a user, I want to filter my task list by "High," "Medium," and "Low" priority, so that I can focus on urgent work first.
Acceptance Criteria:
A dropdown or button toggle is available to select priority levels.


The list updates instantly without a full page reload.


The app clearly indicates which filter is currently active.


2. Organization & Productivity
User Story #3: Mark Task as Complete
As a user, I want to check off a task once finished, so that I can track my progress and keep my list clean.
Acceptance Criteria:
Each task has a checkbox or "Complete" button.


Completed tasks move to a "Completed" section or are visually struck through.


The user can "uncheck" a task if it was marked complete by mistake.


User Story #4: Edit Task Details
As a user, I want to update the title or priority of an existing task, so that I can adjust to changing plans.
Acceptance Criteria:
Clicking a task opens an "Edit" mode or modal.


Changes are only saved once the user clicks "Save" or "Update."


The system confirms the update with a brief toast notification.


3. Security & Account
User Story #5: User Authentication
As a user, I want to create an account and log in securely, so that my personal tasks are saved and private.
Acceptance Criteria:
Users can register with an email and a password of at least 8 characters.


Passswords must be encrypted before being stored in the database.


Only the logged-in user can view, edit, or delete their specific tasks.


