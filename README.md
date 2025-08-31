# Laptop E-Commerce Site

Laptop E-Commerce Site is a web platform that enables users to browse, search, and purchase various laptop models such as Apple and Asus. It is built using HTML, CSS, and PHP to deliver a simple yet dynamic shopping experience.

## Table of Contents

1. Features
2. Project Structure
3. Demo
4. Tech Stack
5. Installation and Setup
6. Usage
7. Future Enhancements
8. Contributing
9. License
10. Contact

## Features

* Multi-brand catalog with separate pages for brands like Apple and Asus
* Dynamic content using PHP for scalability and easier management
* User-friendly navigation with a clean layout
* Database connectivity through connect.php for future support of product data
* Consistent styling managed by a single CSS file (Demo3.1.css)

## Project Structure

Laptop-e-commerce-site/
├── Apple.html
├── Apple.php
├── Asus.html
├── Asus.php
├── Home.html
├── Home.php
├── connect.php
└── Demo3.1.css

Brand pages are available in both HTML and PHP formats to support static and dynamic rendering. Home pages are included in both formats as the entry point to the site. The connect.php file is used for configuring and connecting to a backend database. Demo3.1.css is the stylesheet that defines the overall styling of the site.

## Demo

(Optional: Add screenshots or a live demo link if available.)

## Tech Stack

Frontend: HTML, CSS
Backend: PHP
Styling: Central stylesheet

## Installation and Setup

1. Clone the repository

   git clone [https://github.com/PranavFWL/Laptop-e-commerce-site.git](https://github.com/PranavFWL/Laptop-e-commerce-site.git)
   cd Laptop-e-commerce-site

2. Set up a local server using XAMPP, WAMP, MAMP, or any PHP-enabled server. Place the project folder in the server’s htdocs (or equivalent) directory.

3. Configure connect.php by updating the file with your database credentials:

   ```php
   <?php
   $servername = "localhost";
   $username = "your_db_user";
   $password = "your_db_password";
   $dbname = "your_db_name";

   $conn = new mysqli($servername, $username, $password, $dbname);

   if ($conn->connect_error) {
     die("Connection failed: " . $conn->connect_error);
   }
   ?>
   ```

4. Launch the site by navigating to [http://localhost/Laptop-e-commerce-site/Home.php](http://localhost/Laptop-e-commerce-site/Home.php) (or Home.html) in your browser.

## Usage

* Use the navigation menu to move between the home page and brand-specific sections
* Switch to PHP versions of the pages for dynamic features
* Extend connect.php to integrate product listings, payments, user accounts, or admin panels

## Future Enhancements

* Full database integration for dynamic product listings, categories, and pricing
* User authentication with login and registration functionality
* Shopping cart and checkout system with payment integration
* Admin dashboard for product management and order tracking
* Responsive design for better mobile and tablet support
* Enhanced styling with modular CSS and animations

## Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch for your feature or fix
3. Make the changes and test thoroughly
4. Submit a pull request with a clear description of your work


