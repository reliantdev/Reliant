## Full Stack
Welcome to Your Technical Challenge!

As part of our interview process, we're excited to present you with a real-world coding task designed to showcase your skills as a full-stack software engineer. 
We believe in seeing our candidates in action, understanding not just what you can do, but how you think and solve problems.

#### Your Task:

You will be developing a simple User Support Ticket System. This system is intended to help a fictional organization manage user inquiries and issues effectively. 
Through this project, you will create a platform where users can submit support tickets, view their status, and update them as necessary.

#### Why This Project?

We've chosen this project because it mirrors common tasks you might face while working with us and involves a balanced mix of both front-end and back-end skills. 
It's a great way to demonstrate your ability to construct a complete web application from scratch.

#### What We're Looking For:

- Creativity and Initiative: Feel free to impress us with your approach to solving user needs.
- Technical Proficiency: Show off your coding skills and your ability to work with different technologies and frameworks.
- Problem Solving: We're interested in your thought process and how you tackle challenges in software development.
- Understanding of Web Fundamentals: Demonstrate your grasp of how web servers and browsers communicate and interact, and how to effectively separate front-end and back-end concerns.

This is your opportunity to shine and demonstrate why you're the right fit for our team. We look forward to seeing your innovative solutions and discussing your development choices.

Good luck, and most importantly, have fun with it!

## User Support Ticket System

Project Brief: User Support Ticket System

Objective: Build a simple user support ticket system that allows users to create, view, and update support tickets.

Requirements:
1. User Interface (Front-end)
    - Ticket Submission Form: Allows users to submit new support tickets with fields for the title, description, and priority level.
    - Ticket Dashboard: A view to list all tickets with basic filtering capabilities (e.g., by status or priority).
    - Ticket Details View: Users can click on a ticket in the dashboard to view full details and update the status of the ticket (e.g., Open, In Progress, Resolved).
2. Server-side (Back-end)
    - API Endpoints:
      - POST /tickets to submit a new ticket.
      - GET /tickets to retrieve all tickets.
      - GET /tickets/{id} to retrieve a specific ticket's details.
      - PUT /tickets/{id} to update a ticket’s status.
    - Data Storage: Implement simple data storage to persist tickets. This can be a database or an in-memory solution for simplicity.

3. Documentation:
    - A brief explanation of the architecture.
    - Setup and installation instructions.
    - A simple discussion of the decision-making process behind the chosen technologies and design.

Evaluation Criteria:

  1. Functionality: The basic functionalities must work as expected without bugs.
  2. Code Quality: Readability, maintainability, and organization of code.
  3. Design Decisions: Understanding of front-end and back-end separations, choice of frameworks and libraries, and the rationale behind these choices.
  4. Scalability and Security Considerations: Even if advanced scalability and security aren't implemented due to time constraints, candidates should be prepared to discuss how they would improve their solution in these areas.

Optional Extensions:

- Implement authentication for users to only view and edit their tickets.
- Add real-time updates to the dashboard using WebSockets.
- Deploy the application to a cloud provider like Azure, using Azure Web Apps or Containers.
