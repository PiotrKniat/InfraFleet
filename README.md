# InfraFleet - IT Infra & Server Fleet Manager

## Overview
InfraFleet is a modern web application prototype designed for centralized IT infrastructure management. This repository contains the **Static UI Mockup** created as an individual project for the Software Engineering course. 

The system acts as a central registry for all servers and workstations within an organization, simulating the ability to execute remote administrative tasks directly from a web browser without the need for manual SSH connections.

## Key Features
* **Server Inventory Management:** Add new servers to the registry, view their current status (Online/Offline), and delete decommissioned machines.
* **Smart Input Validation:** Built-in JavaScript logic that validates IPv4 formats and prevents duplicate IP entries in the database.
* **Task Execution Console:** A simulated terminal that mimics running remote tasks (e.g., restarting Nginx, updating packages) and streams the execution logs directly to the UI.
* **Responsive Design:** A clean, modern interface that scales perfectly on desktop and mobile devices.

## Technology Stack
This phase of the project is implemented as a static frontend prototype to validate UI/UX and system requirements:
* **Markup & Styling:** HTML5, CSS3
* **CSS Framework:** Bootstrap 5 (via CDN)
* **Interactivity & Logic:** Vanilla JavaScript (ES6)

## How to Run Locally
Since this is a static UI prototype, there is no need to set up a backend server or a database.

1. Clone this repository to your local machine:
   ```bash
   git clone <repository_url>
2. Navigate to the project folder.

3. Simply open the login.html file in any modern web browser (e.g., Chrome, Firefox, Edge).

4. Click the Login button (default credentials can be left as-is) to access the main Dashboard and interact with the system.

Future Development (Roadmap)
In a full production environment, this frontend would be integrated with:

A RESTful API backend (e.g., Python FastAPI/Flask).

A relational database (e.g., PostgreSQL).

Configuration management tools (e.g., Ansible, SaltStack) for real-time remote task execution.
