# final-project
final project CF6


**Electric Appliances E-Shop**

Overview

This project is a dynamic e-commerce website designed to sell electric appliances, built using a combination of front-end and back-end technologies. The website offers a full shopping experience, including features such as user registration, login/authentication, personalized user data storage and editing, a shopping cart, and a checkout process.

**Technologies Used**

**Front-End**:

HTML (Hypertext Markup Language): The backbone of the website, HTML is used to structure the content on each page, including product listings, categories, and user forms (registration, login, etc.).

CSS (Cascading Style Sheets): CSS is employed to style the website, ensuring it’s visually appealing and responsive on different devices. It handles layout, colors, fonts, and positioning of elements.

JavaScript: JavaScript adds interactivity to the website, enabling functionalities such as form validation, dynamically updating the shopping cart, and interactive product details.

**Back-End**:

PHP: PHP is used to manage the server-side logic, including user authentication (login/register), handling form submissions, processing the shopping cart, and managing database queries for product listings and user data.

SQL/MariaDB: The database stores essential information, such as user accounts, product data, and transaction history. MariaDB is used for its robust relational database management system to ensure smooth and secure data handling.

**Features**

1. User Registration & Authentication:
Users can create an account and log in to the site, allowing them to save their data for future purchases.
The system handles the authentication process, ensuring secure login/logout functionality. Authentication is the process of verifying the identity of a user by checking their credentials (username and password).
Once authenticated, users can access their personalized profile and make changes to their details, such as updating their personal information.
Authorization ensures that only the authenticated user has access to their own data, like their shopping cart and order history, and prevents unauthorized access to other users' information.

2. Product Listings & Categories:
Products are listed in categories, such as "Home Appliances," "Kitchen Appliances," etc., for easy navigation.
Each product has a description, price, and image, providing users with a full view of what they are purchasing.

3. Shopping Cart:
Users can add items to their shopping cart, which will persist while they browse the site.
Cart functionality includes the ability to update quantities or remove items.

4. Checkout (Cash-Out) Process:
The checkout process allows users to confirm their orders, review the cart, and proceed to payment.
Payment processing and order completion simulate a real-world e-commerce experience, ensuring the website behaves like a real online store.

**Technical Description**

**Front-End Development**:

HTML structures the webpage, including elements like the header, footer, product grid, and user forms.

CSS ensures a responsive layout, ensuring the site looks great on mobile and desktop devices.

JavaScript is used for interactive elements such as dynamically updating the shopping cart without refreshing the page and providing a smooth user experience.

**Back-End Development**:

PHP is the core programming language for server-side scripting. It handles logic such as processing form data, managing sessions for logged-in users, and interacting with the database for retrieving product information or updating user data.

MariaDB is used to manage the website’s database. It stores user details, product information, and transaction records in an organized manner, allowing for efficient queries and updates.


**Database Schema**

Users Table: Stores user information such as username, password (hashed for security), email, and personal details.

Products Table: Contains product details like name, description, price, stock quantity, and category.

Orders Table: Keeps track of user orders, including product IDs, quantities, and payment details.


**How to Run the Project**

Clone the repository to your local machine.
Set up a local server environment using tools like XAMPP:
Download and install XAMPP.
Launch XAMPP Control Panel, and start both Apache (for PHP) and MySQL (for MariaDB).
Import the provided SQL file into your MariaDB database using phpMyAdmin (accessible via http://localhost/phpmyadmin).
Place the project files in the htdocs folder inside the XAMPP installation directory.
Open your browser and navigate to http://localhost/your_project_folder to run the website locally.


**Future Enhancements**
Implementing payment gateways for real transactions.
Adding an admin panel for product and order management.
Improving user interface and user experience (UI/UX).
