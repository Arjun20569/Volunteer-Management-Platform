
# Online Volunteer Management Platform


## Project Summary
The **Online Volunteer Management Platform** is designed to connect organizations with volunteers. It allows organizations to post volunteer opportunities, enables volunteers to sign up for them, and provides administrators with control over user and content management.

## Project Description
The platform serves as a bridge between organizations and volunteers, where:
- **Organizations** can post and manage volunteer opportunities.
- **Volunteers** can sign up for events and track their participation and hours.
- **Administrators** oversee users, manage volunteer listings, and handle system settings.


## User Types and Functionalities

### 1. Admin
The Admin role is responsible for user and content management, with the following functionalities:
- **User Management**
  - **Input:** User details (name, email, role)
  - **Output:** Confirmation of successful user creation, update, or deletion
  - **Functionality:** Manage user accounts and roles.
- **Volunteer Listings Management**
  - **Input:** Listing details (opportunity, date, location)
  - **Output:** Approval or rejection status
  - **Functionality:** Approve or reject volunteer listings submitted by organizations.
- **System Settings**
  - **Input:** Configuration settings
  - **Output:** Confirmation of successful settings update
  - **Functionality:** Manage system-wide settings.

### 2. Organization
Organizations post and manage volunteer opportunities, with functionalities to interact with volunteers:
- **Post Volunteer Opportunities**
  - **Input:** Opportunity details (description, date, location)
  - **Output:** Confirmation of successful posting
  - **Functionality:** Post volunteer opportunities.
- **Interact with Volunteers**
  - **Input:** Interaction details (messages, feedback)
  - **Output:** Confirmation of successful interaction
  - **Functionality:** Communicate with volunteers.
- **Track Volunteer Participation**
  - **Input:** Participation details
  - **Output:** Participation reports
  - **Functionality:** Track and view volunteer participation.

### 3. Volunteer
Volunteers can explore and sign up for opportunities and interact with organizations:
- **Sign Up for Opportunities**
  - **Input:** Opportunity selection
  - **Output:** Confirmation of successful sign-up
  - **Functionality:** Sign up for volunteer opportunities.
- **Track Volunteer Hours**
  - **Input:** Volunteer hours details
  - **Output:** Hours summary
  - **Functionality:** Track and view volunteer hours.
- **Interact with Organizations**
  - **Input:** Interaction details (messages, feedback)
  - **Output:** Confirmation of successful interaction
  - **Functionality:** Communicate with organizations.

## Dashboards

### Admin Dashboard
- **User Management:** View and manage user accounts with roles and statuses.
- **Volunteer Listings Management:** See all volunteer listings and approval statuses.
- **System Settings:** Configure and view system settings.
- **Participation Overview:** View volunteer participation stats and pending approvals.

### Organization Dashboard
- **Post Opportunities:** Interface for posting and managing volunteer opportunities.
- **Volunteer Interaction:** Manage communications with volunteers.
- **Participation Tracking:** View signed-up volunteers and track participation.

### Volunteer Dashboard
- **Available Opportunities:** Browse and sign up for volunteer opportunities.
- **My Sign-Ups:** Track the status of signed-up opportunities.
- **Hours Tracking:** Log and view volunteer hours.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Java (Spring Boot)
- **Database**: MySQL
- **Server**: Apache Tomcat

## Installation
1. Clone the repository:
   git clone https://github.com/yourusername/online-volunteer-management-platform.git

  <h2>📸 Screenshots</h2>
  <h3>Home Page</h3>
  <img src="https://github.com/user-attachments/assets/ff0ab591-9add-49f6-96c5-521ce66d877b" alt="Home Page">
  
  <h3>Search Page</h3>
  <img src="https://github.com/user-attachments/assets/e37c28c8-6806-471f-a211-79af539e60fd" alt="Search Page">
  
  <h3>Login Page</h3>
  <img src="https://github.com/user-attachments/assets/8dfbf30c-14d9-433c-a730-3c247c6b4f4e" alt="Login Page">
  
  <h3>Register Page</h3>
  <img src="https://github.com/user-attachments/assets/3b4eac63-4831-4ba2-a53f-fe492ae87f23" alt="Register Page">
