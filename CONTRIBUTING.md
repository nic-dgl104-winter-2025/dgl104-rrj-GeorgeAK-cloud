

# CONTRIBUTING.md

## Project Title: AI-Powered Smart Task Management System (STMS)

### Contributors:
- George Akaeze  
- Abdulbasit Aawofeso  
- Tien Phat Pham

---

## Project Overview

The AI-Powered Smart Task Management System (STMS) is a scalable web-based application built with PHP and MySQL. It is designed to support task creation, assignment, tracking, and collaboration among users. This system provides role-based access, intelligent task prioritization, and automated assignment while maintaining security and modular architecture. It serves as a platform to apply design patterns, CI/CD, testing, debugging, and refactoring best practices in a real-world development environment.

## Objective
This project aims to:

1. Implement four or more design patterns: Factory, Observer, Singleton, and Decorator.

2. Develop a modular and maintainable architecture.

3. Set up CI/CD pipelines for testing and deployment via GitHub Actions.

4. Employ debugging and logging techniques.

5. Adhere to security best practices including input validation and session handling.



## Weekly Reflections & Contributions

### **Week 9 – Design Patterns & Open Source Contributions**
We explored reusable software design patterns.  
**Implemented:**
- Factory Pattern for dynamically creating user roles.
- Singleton Pattern for ensuring a single database connection instance.
- Observer Pattern for sending real-time task status notifications.

**Team Reflections:**
- George designed the Factory role handler and wrote pseudocode for team review.
- Abdulbasit implemented the Observer mechanism for notifications.
- Tien explored design improvements for the Singleton DB connector and added unit tests.

### **Week 10 – Architectural Patterns & MVP Structure**
We focused on Model-View-Controller (MVC) architecture to improve system modularity.

**Implemented:**
- MVC-style folder structure to separate logic, data, and presentation.
- Controller for handling task CRUD operations.
- Views using modular PHP templates for scalability.

**Team Reflections:**
- Tien structured the MVC pattern and improved HTML/PHP templates.
- George refactored controllers and wrote helper functions.
- Abdulbasit wrote validation logic and added database seeding scripts.

### **Week 11 – UI Improvement, Debugging & Logging**
We improved the user interface, implemented input validation, and began logging activities.

**Implemented:**
- Responsive UI using Bootstrap.
- Logging mechanism for tracking task updates.
- Basic debugging with console logs and PHP error handlers.

**Team Reflections:**
- George created a debugging checklist.
- Abdulbasit implemented input sanitization.
- Tien integrated logging into the task update pipeline.

### **Week 12 – Functional Programming**
We learned functional programming principles and applied declarative programming where applicable.

**Implemented:**
- PHP functional array methods (`array_filter`, `array_map`) for cleaner logic.
- Separated logic into small reusable functions for task filtering and transformation.

**Team Reflections:**
- Tien optimized filtering logic for completed tasks.
- Abdulbasit applied array mapping for task priority indicators.
- George ensured that functions were stateless and reusable.

### **Week 13 – Final Features & Security**
This week focused on refining the app, enhancing security, and preparing for deployment.

**Implemented:**
- Role-based authentication and session validation.
- Secure database queries with prepared statements (PDO).
- Final code refactoring and feature polishing.

**Team Reflections:**
- Abdulbasit implemented prepared statements to prevent SQL injection.
- Tien handled form validation and error display logic.
- George managed GitHub workflows and coordinated merge requests.

---

## 🛠️ Development Practices Followed
- **Code Reviews**: Conducted through GitHub Pull Requests.
- **CI/CD**: Automated test and deploy pipeline using GitHub Actions.
- **Debugging**: Logged server-side events and validated frontend interactions.
- **Security**: Input sanitization, password hashing, and session validation.
- **Refactoring**: Removed duplicate code, organized logic, and renamed variables for clarity.

---

##  Issues & Resolutions

- **Issue**: Session not expiring properly after logout.  
  **Resolved by**: George introduced session_destroy() and added redirect logic.

- **Issue**: Task priorities weren’t reflecting visually.  
  **Resolved by**: Tien used conditional Bootstrap badges in task view.

- **Issue**: Task updates were not tracked.  
  **Resolved by**: Abdulbasit added timestamp logs on each task update and notification.

---

##  Future Improvements
- Add a Kanban view with drag-and-drop functionality.
- Integrate a lightweight AI engine to recommend task priorities.
- Enhance role permission system with custom scopes.
- Improve real-time updates with WebSockets or Firebase.

---

##  How to Contribute (If Extending the Project)
1. **Fork** the repository.
2. Create a new branch: `git checkout -b feature-name`
3. Make your changes with clean, commented code.
4. Write unit tests if applicable.
5. Commit and push to your branch: `git push origin feature-name`
6. Open a Pull Request and link it to an issue if one exists.