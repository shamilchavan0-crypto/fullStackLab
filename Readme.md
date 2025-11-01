Introduction
This document is a portfolio of 12 lab exercises from my Full Stack Development course. The labs guided me from backend services with Node.js and Express, through database modeling with Sequelize, to frontend development using React, culminating in a fully integrated application.
This journal details:

The specific tasks assigned for each lab

The technical concepts put into practice

The primary tools and packages used

Personal takeaways and understanding gained

Lab-Wise Work Journal
Lab 1 — Node.js + Express Basics
Initialized a Node project using npm init.

Launched a simple HTTP server using the Express framework.

Handled basic HTTP methods (GET/POST) and sent responses.

Concepts: Node.js environment, server instantiation, HTTP verbs, request/response.

Lab 2 — Using Lodash Utility Library
Integrated the Lodash library as a project dependency.

Utilized helper functions (e.g., _.filter, _.debounce) for data manipulation.

Concepts: Dependency management, third-party modules, utility functions.

Lab 3 — Error Handling, Callbacks & Event Emitters
Implemented a global error-handling middleware.

Managed asynchronous operations using the callback pattern.

Used Node's EventEmitter for decoupled communication between modules.

Concepts: Error propagation, asynchronous patterns, event-driven design.

Lab 4 — Reminder Application
Leveraged setTimeout for delayed execution and setInterval for recurring tasks.

Used event emitters to broadcast notification events.

Built API endpoints for creating and managing reminders.

Concepts: Node.js timers, event listeners, API construction.

Lab 5 — Routing & Streams (with Pipe)
Refactored routing logic into modular files using express.Router().

Managed file I/O efficiently using Node.js Streams.

Piped a readable stream directly to a writable stream.

Concepts: Route organization, data pipelines, resource management, I/O.

Lab 6 — Cron Jobs
Used the node-cron library to schedule automated tasks.

Set up a recurring job to run at a specific time (e.g., "every 5 minutes").

Verified job execution by logging output to the console.

Concepts: Task automation, cron syntax, background scripts.

Lab 7 — Sequelize Connection Setup
Installed the Sequelize ORM package and the required database driver (e.g., pg).

Configured the database credentials and confirmed a successful connection.

Concepts: ORM layer, database dialects, connection pooling, initialization.

Lab 8 — User Model & Queries
Modeled a User table, defining its schema (columns and data types).

Executed CRUD operations (Create, Read, Update, Delete) using Sequelize's API.

Concepts: Schema definition, database abstraction, model interface, data persistence.

Lab 9 — Sequelize Model Associations
Established a One-to-One relationship (e.g., User and Profile).

Created a One-to-Many relationship (e.g., User and Posts).

Built a Many-to-Many relationship using a join table (e.g., Posts and Tags).

Concepts: Data association, relational integrity, foreign keys.

Lab 10 — React Setup
Scaffolded a new React application using npx create-react-app.

Organized the src directory and reviewed the project scripts.

Employed useState for component state and useEffect for side effects.

Concepts: Frontend tooling, component state, React Hooks, JSX.

Lab 11 — Creating Components (Home, About, Contact)
Developed modular and reusable UI components for different pages.

Implemented client-side navigation using react-router-dom.

Managed data flow from parent to child components via props.

Concepts: UI composition, Single Page Application (SPA) routing, "prop drilling".

Lab 12 — Frontend & Backend Integration
Connected the React client to the Express API using the axios library.

Fetched and rendered server-side data dynamically within React components.

Resolved Cross-Origin Resource Sharing (CORS) issues on the server.

Concepts: Full-stack communication, API consumption, data fetching, async/await.

Concepts I Found Challenging
Integration
Troubleshooting CORS policy errors was a frequent challenge.

Learned to properly manage asynchronous state (loading, data, error) on the frontend.

Gained a clear understanding of bridging the client-server gap.

File Streaming
Grasping the abstract concepts of buffers and chunks was difficult at first.

Visualizing the flow of data through the .pipe() mechanism helped clarify it.

Came to understand the significant memory benefits for large files.

User Queries
Translating complex SQL logic (especially joins) into Sequelize's ORM methods.

Learning to use the include option effectively for associated data.

Became comfortable handling the asynchronous, promise-based nature of database queries.

Context Handling
Deciding on the correct state management strategy (local state vs. global context).

Implementing the React Context API to avoid passing props through many layers.

Using context to share global information, like authenticated user status.

Conclusion
This journal charts my development from isolated backend scripts to a cohesive, full-stack application. The 12 labs provided a pragmatic, end-to-end overview of modern web development principles and practices.
