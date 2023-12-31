# Point of Sales System
Group Project for SENG 3000: Architecture and Design

This project aims to develop a point of sale (POS) system that will streamline the sales process,
enhance user experience, and provide valuable insights for businesses. The System will have an
interactive graphic user interface, prioritize accessibility, and ensure adaptability to cater to
various business types.

In this project, the POS system will provide specific features, such as:
1. Interactive Point & Click:
a. Intuitive Design: Create a user-friendly interface that is easy to navigate and
minimizes training time for employees.
b. Customizable Layout: Allowing businesses to customize the layout to match their
specific needs, including product categories, pricing, and branding.

2. Accessibility:
a. Screen Reader Support: Implement screen reader compatibility for visually
impaired users.
b. Keyboard Navigation: Ensure full functionality using keyboard shortcuts for users
with limited mobility.
c. High-Contrast Mode: Offer a high-contrast mode for users with visual
impairments.

3. Software Adaptability:
a. Multi-Platform Compatibility: Develop the POS system to work on various
platforms, including Windows, macOS, and web-based versions.
b. Modular Architecture: Design the system with a modular architecture to easily
add or remove features based on business requirements.
c. Scalability: Ensure the system can handle the needs of small local stores as well
as large retail chains.

4. Data Analytics:
a. Sales Reports: Provide real-time sales reports and analytics to help businesses
track performance and make data-driven decisions.

b. Inventory Management: Implement inventory tracking and alerts to avoid
stockouts and overstock situations.
c. Customer Insights: Gather and analyze customer data to personalize marketing
strategies and improve customer retention.

# Notes for Team Members
I'm using Visual Code yet, any other IDE can work.
Use these dotnet CLI commands in order to work on this project:
```
dotnet add package Microsoft.EntityFrameworkCore
dotnet add package Microsoft.EntityFrameworkCore.Design
dotnet add package Microsoft.EntityFrameworkCore.Tools
dotnet add package Microsoft.EntityFrameworkCore.Sqlite
dotnet add package Microsoft.EntityFrameworkCore.SqlServer
dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design
```
```
// COMPLETED: Create DbContext files

// COMPLETED: Create 3 different models 

// COMPLETED: Must create at least 4 different endpoints using 2 different models

// TODO: Create and validate username and a password from a user database table that contains hashed passwords

// COMPLETED: Create two users predefined in user table with different roles (one of front of house and a manager)

// TODO: Role and username/email address must be included in JWT claims

// TODO: Must return an appropriate http status code if authentication failed

// TODO: Create at least FIVE pages for the website layout

// TODO: Create Login Page
```
