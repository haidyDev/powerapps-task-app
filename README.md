# Power Apps Task Management App (Work in Progress)

A simple task management solution built using Microsoft Power Apps, SharePoint, and Power Automate.

This project combines a Canvas app with backend data storage and automation to demonstrate a practical low-code business solution.

---

## Overview

The application allows users to create and manage tasks with key attributes such as title, description, due date, and priority.

In addition to the app itself, a Power Automate flow is used to trigger notifications when new tasks are created.

This project was built as part of learning Microsoft Power Platform and developing real-world low-code solutions.

---

## Features

### Task Management (Power Apps)

- Create tasks with:
  - Title
  - Description
  - Due date
  - Priority (High / Normal / Low)
- Display tasks in a structured gallery layout
- Delete tasks
- Clean and readable UI layout

### Data Storage (SharePoint)

- Tasks stored in a SharePoint list
- Supports text, date, and choice fields
- Acts as backend for the app

### Automation (Power Automate)

- Trigger: When a new task is created
- Condition: If task priority is **High**
- Action: Send an email notification

This demonstrates event-driven automation and integration between services.

---

## Tech Stack

- Microsoft Power Apps (Canvas App)
- SharePoint (List as data source)
- Power Automate
- Power Fx

---

## Screenshots

### App View
![App view](app-main.png)

### Power Automate Flow
![Flow](flow-overview.png)

---

## Current Status

Work in progress.

The current version focuses on:
- Core functionality
- Clean layout
- Basic automation

Further improvements will be made to enhance usability, UI consistency, and additional features.

---

## What I Learned

Through this project, I practiced:

- Building a Canvas app with Power Apps
- Connecting Power Apps to SharePoint
- Using Power Fx functions such as:
  - `Patch`
  - `Refresh`
  - `Remove`
- Working with gallery layouts and UI structure
- Handling SharePoint data types (Choice, Date)
- Creating automated flows with Power Automate
- Implementing conditional logic in automation

---

## Next Steps

Planned improvements:

- Improve UI polish and consistency
- Add input validation
- Add search and filtering functionality
- Enhance user experience
- Expand automation (e.g. reminders)

---

## Author

Heidi Maunu  
[LinkedIn](https://www.linkedin.com/in/heidimaunu/)
