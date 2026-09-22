# Interactive Task Manager

A browser-based task manager application developed for the MSTCONNECT PH Full-Stack Web Development Intensive Bootcamp (Session 8: DOM, Events, JSON & Browser Storage). This application provides a data-driven web interface allowing users to add, display, complete, edit, delete, and persist tasks directly in the browser.

---

## 📌 Features

### Core Capabilities
* **Add Tasks**: Submit new tasks using an interactive form.
* **Dynamic DOM Rendering**: Render tasks dynamically into the web page markup.
* **Input Validation**: Validates user inputs before saving, rejecting empty submissions and requiring a minimum title length of 3 characters.
* **Toggle Completion**: Mark tasks as complete or incomplete with visual strike-through updates.
* **Delete Tasks**: Remove individual tasks from state and UI.
* **Edit Tasks**: Update task titles interactively via modal prompts.
* **Data Persistence**: Retains task items across browser reloads using `localStorage` and JSON conversion.

### Challenge Upgrades
* **Completed Task Counter**: Tracks and displays completed task counts relative to total tasks.
* **Clear Completed Tasks**: Removes all finished tasks in a single click.
* **Task Filtering**: Filters the displayed list by status (`all`, `active`, `completed`).
* **Duplicate Prevention**: Prevents adding task titles that already exist in state (case-insensitive).

---

## 📂 Project Structure

```text
session-08-task-manager/
├── index.html        # Main HTML markup and structure
├── css/
│   └── style.css     # Visual styling and layout
└── js/
    └── app.js        # State logic, DOM handling, and persistence