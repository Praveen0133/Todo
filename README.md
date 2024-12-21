Todo List Application 📝
A modern to-do list application built with React, featuring drag-and-drop functionality, persistent storage using local storage, and unique task IDs generated with UUID.

Features
Add Tasks: Quickly add tasks with a unique identifier.
Delete Tasks: Remove tasks by their unique ID.
Drag & Drop: Rearrange tasks using an intuitive drag-and-drop interface.
Persistent Storage: Tasks are saved to local storage for seamless browser sessions.
Unique Task IDs: Every task is assigned a unique ID using UUID for reliable operations.
Tech Stack
React: For building the interactive user interface.
Tailwind CSS: For styling the application.
JavaScript: For application logic, drag-and-drop, and local storage integration.
UUID: For generating unique task IDs.
Local Storage: To persist tasks across sessions.
Usage
Add Tasks: Enter a task name and click the "Add" button.
Drag & Drop: Drag tasks to reorder them.
Complete Tasks: Mark tasks as completed by clicking the checkbox.
Delete Tasks: Remove tasks using the delete button.
Persistent Data: Refresh the page — your tasks remain, thanks to local storage.
How It Works
Unique Task IDs with UUID
UUID Generation: Each task is assigned a unique ID using the UUID library.
Reliable Operations: IDs ensure precise identification for editing, deleting, and reordering tasks.
Drag & Drop
React DnD or Custom Logic: Used to enable task reordering through drag-and-drop.
State Management: Updates the task list state on drop and syncs it with local storage.
Local Storage
Save Tasks: Stores the task list as a JSON array in local storage.
Retrieve Tasks: Loads tasks from local storage when the app initializes.
Update Storage: Keeps local storage synced whenever tasks are added, removed, or reordered.
