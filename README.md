ProjectFlow - Collaborative Project Management Tool
Overview
ProjectFlow is a web-based project management application built with HTML, JavaScript, and Tailwind CSS. It provides a Kanban-style interface for managing projects and tasks, featuring user authentication, real-time updates, and team collaboration capabilities. Users can create projects, assign tasks, track progress, and communicate through comments and notifications.
Features

User Authentication: Login and registration system with demo accounts for immediate access.
Project Management: Create, view, and manage multiple projects with customizable details (name, description, due date, priority).
Kanban Board: Organize tasks in columns (To Do, In Progress, Review, Done) with drag-and-drop functionality.
Task Management: Create, edit, and delete tasks with assignees, priorities, due dates, and progress tracking.
Comments & Activity: Add and view comments on tasks for team collaboration.
Notifications: Real-time notifications for task updates, comments, and team activities.
Responsive Design: Fully responsive UI optimized for desktop and mobile devices.
Real-time Simulation: Simulated WebSocket updates for team activities and notifications.

Getting Started
Prerequisites

A modern web browser (e.g., Chrome, Firefox, Edge).
No server setup is required as the application runs entirely in the browser with client-side JavaScript.

Installation

Clone or Download:

Clone the repository or download the source code.
Ensure you have the index.html file and associated assets.


Run the Application:

Open index.html in a web browser. No additional server setup is required.
Alternatively, serve the file using a local development server (e.g., npx live-server).


Demo Accounts:

Use the following credentials to log in and explore the application:
Email: shashank@projectflow.com | Password: password123
Email: priya.reddy@projectflow.com | Password: password123
Email: arjun.rao@projectflow.com | Password: password123





Usage

Login or Register:

Use a demo account or create a new account via the registration form.
After logging in, you'll be directed to the main dashboard.


Project Management:

Create a new project using the "New Project" button.
Select team members, set due dates, and assign priorities.
Switch between projects using the project dropdown.


Task Management:

Add tasks to specific columns on the Kanban board.
Drag and drop tasks between columns to update their status.
Click a task to view details, add comments, or edit properties.


Notifications:

View notifications by clicking the bell icon in the header.
Notifications include task updates, new comments, and team activities.


Team Collaboration:

Assign tasks to team members.
Use comments to discuss task progress and updates.



Technical Details
Technologies Used

HTML5: Structure of the application.
JavaScript (ES6): Core logic, state management, and DOM manipulation.
Tailwind CSS: Styling and responsive design.
SVG: Custom avatar generation for users.
No Backend: All data is managed client-side with simulated real-time updates.

Architecture

Class-Based Structure: The ProjectFlowApp class handles state management, UI updates, and event listeners.
Data Storage: In-memory data structures (users, projects, tasks, comments, notifications) simulate a backend.
Drag-and-Drop: HTML5 Drag and Drop API for task movement across Kanban columns.
Notifications: Simulated real-time updates with setInterval for team activities.
Modals: Reusable modal components for creating/editing projects and tasks.

File Structure
projectflow/
├── index.html        # Main application file
└── README.md         # Documentation (this file)

Limitations

Client-Side Only: Data is not persisted across sessions (stored in memory).
No Real Backend: Uses in-memory data and simulated WebSocket updates.
Security: Demo passwords are hardcoded for simplicity; not suitable for production.

Future Improvements

Integrate a backend (e.g., Node.js, Express) for persistent data storage.
Implement real WebSocket or Server-Sent Events for live updates.
Add advanced features like file uploads, task dependencies, and reporting.
Enhance security with proper authentication (e.g., JWT) and password hashing.
Add unit tests for JavaScript logic and UI components.

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a feature branch (git checkout -b feature/YourFeature).
Commit your changes (git commit -m 'Add YourFeature').
Push to the branch (git push origin feature/YourFeature).
Open a pull request.

Please ensure your code follows the existing style and includes appropriate comments.
License
This project is licensed under the MIT License. See the LICENSE file for details.
Contact
For questions or feedback, please contact the project maintainer at shashank@projectflow.com.
