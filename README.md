# inventory-management-sys

Inventory Management System

The goal of this system is to build a light-weight inventory management system for companies who can't afford robust 
systems. This also has the goal of helping companies who build parts out of small components that share functionality 
across different SKU's.
1. **Backend**:
    - **Framework**: Flask
        - Flask is a lightweight and versatile web framework for Python. It's well-suited for building RESTful APIs and 
        - web applications.
    - **Authentication**: Flask-JWT-Extended
        - Flask-JWT-Extended is an extension for Flask that provides JSON Web Token (JWT) authentication support. It 
        - will help you secure your API endpoints and implement user authentication.
    - **Database ORM**: SQLAlchemy
        - SQLAlchemy is a powerful SQL toolkit and Object-Relational Mapping (ORM) library for Python. It allows you to 
        - work with databases using high-level Python objects instead of SQL statements directly.
    - **Database**: SQLite or PostgreSQL
        - SQLite is a lightweight, serverless SQL database engine that's easy to set up and use, making it suitable for 
        - development and testing purposes.
        - PostgreSQL is a robust, open-source relational database management system. It's suitable for production 
        - deployments and offers advanced features for scalability and reliability.
2. **Frontend**:
    - **Framework/Library**: React.js
        - React.js is a popular JavaScript library for building user interfaces. It's component-based, making it easy 
        - to develop reusable UI components.
    - **State Management**: Redux (optional)
        - Redux is a predictable state container for JavaScript apps. It helps manage application state in a consistent 
        - and scalable way, which can be useful for complex frontend applications.
    - **Styling**: CSS (with or without a preprocessor like Sass)
        - Use CSS for styling your frontend components. Sass is a CSS preprocessor that adds features like variables, 
        - mixins, and nesting to CSS, making it more maintainable and organized.
3. **API Design**:
    - Design RESTful APIs using Flask's routing and view decorators. Define endpoints for user authentication, fetching 
    - inventory data, recording sales transactions, etc.
4. **Deployment**:
    - **Hosting Platform**: Heroku
        - Heroku is a cloud platform that allows you to deploy, manage, and scale web applications easily. It supports 
        - Python applications and provides seamless integration with Git for deployment.