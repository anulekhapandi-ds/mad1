# mad1
 The Household Services Application connects customers with service professionals for home services like plumbing and AC repair. Built with Flask, Jinja2, Bootstrap, and SQLite.
This project statement outlines the requirements for a Household Services Application using the Flask framework, Jinja2 templates, and Bootstrap for HTML generation and styling. Here's a structured breakdown of the project:

Project Overview
A multi-user application that provides a platform for home servicing. The users include:

Admin (superuser with root access)
Service Professionals (people who provide services like AC servicing, plumbing, etc.)
Customers (people who book home services)
Frameworks & Technologies
Flask: For server-side application code
Jinja2 + Bootstrap: For HTML generation and styling
SQLite: For the database to store users, services, and service requests
Roles & Their Responsibilities
Admin:

Root access with no registration required.
Can manage and monitor both customers and service professionals.
Create, update, and delete services.
Approve service professionals based on document verification.
Block/unblock users based on poor reviews or fraudulent activity.
Access the Admin Dashboard to manage platform operations.
Service Professional:

Register and login.
Provide services like plumbing, AC repair, etc.
Can view and accept/reject service requests.
Can close service requests upon completion.
Professional profiles include details like experience and customer reviews.
Customer:

Register and login.
Search and view services.
Create and manage service requests.
Close requests once the service is done and leave reviews.
Entities & Terminologies
Service: Represents the home service (e.g., plumbing, AC repair).
Attributes: ID, Name, Base Price, Time required, Description, etc.
Service Request: A request created by a customer for a specific service.
Attributes: ID, service ID, customer ID, professional ID, date of request, date of completion, service status, remarks, etc.
Core Functionalities
Login/Registration:

Admin login redirects to the admin dashboard.
Separate login/register forms for admin, service professionals, and customers.
Admin Dashboard:

Manage users, services, and service professionals.
Approve or block service professionals.
Service Management (Admin):

Create new services with base price and other details.
Edit or delete existing services.
Service Requests (Customers):

Create, edit, and close service requests.
Search Functionality:

Customers: Search services by name, pin code, etc.
Admin: Search professionals for management purposes.
Service Professional Actions:

View and manage service requests.
Recommended Functionalities
Use Flask-RESTful or create custom API resources for users, services, and service requests.
External libraries like ChartJS for creating charts or visualizations.
Implement validation (both frontend using HTML5 or JavaScript and backend in Flask).
Optional Functionalities
Styling with Bootstrap or CSS for a responsive UI.
Flask extensions like Flask-Login for a more secure login system.
Implement a dummy payment system for ad requests or other functionalities.
Evaluation Criteria
Submit a project report (2 pages max) including:
Student details and project details
Frameworks and libraries used
ER diagram of the database
API resource endpoints (if any)
A video explaining the project approach (5-10 minutes)
The project zip file and a presentation video link.
Instructions
Regular updates may be made to the document, with a final freeze by September 19, 2024.
The project must be submitted as a single zip file.
Do you need assistance with any specific part of this project, such as developing the structure or setting up the Flask environment?
