# TaskBuddy
Task Management App with Email Notification and easy sharing capabilities.


Tech Stack:

    Frontend: React.js 

    Backend: Django 
        Easy to integrate with databases and has built-in user authentication features.

    Database: ElephantSQL - online psql

    Email Service: SendGrid or Amazon SES
        For reliable email notifications.

    Hosting: AWS EC2 or Heroku
        To make your app accessible online.

    Version Control: GitHub 

Project Name:

    TaskBuddy
        These names are catchy and relate well to task management.

SQL Database Schema:

    Users Table
        user_id: Primary Key
        username: Text
        password: Text (hashed)
        email: Text

    Tasks Table
        task_id: Primary Key
        user_id: Foreign Key (linked to Users Table)
        title: Text
        description: Text
        due_date: DateTime
        priority: Integer
        status: Enum (Incomplete, Complete)

    Share Table
        share_id: Primary Key
        task_id: Foreign Key (linked to Tasks Table)
        shared_with: Text (email or username)

Steps Until Deployment:

    Project Initialization
        Create a new project repository on GitHub or GitLab and clone it locally.

    Backend Setup
        Initialize your chosen backend framework and set up the database connection.

    User Authentication
        Implement sign-up, login, and logout features.

    CRUD for Tasks
        Implement Create, Read, Update, and Delete operations for tasks.

    Email Notifications
        Integrate email service for notifications.

    Task Searching
        Add a search functionality based on task title or tags.

    Quick Sharing
        Add a feature to quickly share tasks, akin to ix.io.

    Frontend Development
        Create the UI using your chosen frontend framework.

    Testing
        Test all features thoroughly.

    Deployment
        Deploy the app using AWS EC2 or Heroku.

    Maintenance and Updates
        Keep the app updated and fix any emerging bugs or issues.