# Internship Management App

A custom ERPNext/Frappe application developed to manage internship tasks and track internship activities.

## Project Overview

The Internship Management App is a custom application created as part of an internship project. It provides a simple system for creating, managing, and tracking internship tasks.

## Features

- Create and manage internship tasks
- Track task status
- Set task priority
- Record intern details
- Set start and end dates
- Add task descriptions

## Custom Module

### Internship Management

The application contains a custom **Internship Management** module.

### Internship Task

The Internship Task DocType is used to record and manage internship work.

## Technologies Used

- Frappe Framework
- ERPNext
- Python
- JavaScript
- MariaDB
- Redis
- Git & GitHub

## Installation

From the Frappe Bench directory:

    bench get-app internship_app
    bench --site erpnext.localhost install-app internship_app
    bench --site erpnext.localhost migrate

## Usage

1. Open ERPNext.
2. Open the **Internship Management** module.
3. Open **Internship Task**.
4. Create a new internship task.
5. Enter the required details.
6. Save the task.
7. Track its status and priority.

## Project Result

The application provides a custom internship task management system inside ERPNext.

## License

MIT License
