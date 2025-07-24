# Laporkuy

Laporkuy is a web application developed as a final project for an advanced web programming course. It aims to empower urban communities by providing a platform for public reporting, directly contributing to **Sustainable Development Goal (SDG) 11: Sustainable Cities and Communities**. This application facilitates citizen engagement in improving urban environments by enabling easy and precise reporting of various community issues.

---

## Features

Laporkuy comes equipped with essential features designed for efficient reporting and user interaction:

* **Simple Landing Page**: An intuitive and user-friendly entry point for all users.
* **User Authentication**: Secure user registration and login functionalities, powered by **Laravel Breeze**, to manage access and personalize the reporting experience.
* **Comprehensive CRUD Operations**: Full Create, Read, Update, and Delete capabilities for managing reported issues, ensuring data flexibility and control.
* **Database Integration**: Robust data management handled by **MySQL**, ensuring all reports and user data are stored securely and efficiently.
* **Interactive Map Integration**: Seamlessly integrates **OpenStreetMap (OSM)** and **Leaflet.js** to provide an interactive map where users can accurately pinpoint the location of their reports.
* **Nominatim API for Geocoding**: Utilizes the **Nominatim API** on top of OSM to convert addresses into geographical coordinates and vice-versa, enhancing the accuracy and detail of location-based reports.

---

## Technologies Used

This application is built using a modern and efficient stack:

* **PHP Framework Laravel (Breeze)**: The core backend is powered by the robust Laravel framework, with **Laravel Breeze** providing rapid scaffolding for authentication.
* **Tailwind CSS**: A utility-first CSS framework used for building a highly customizable and responsive user interface.
* **MySQL**: The relational database management system chosen for its reliability and performance in handling application data.

---

## Access & Setup

You can access the live application here: **(https://laporkuy.unaux.com/)**

To run this application locally, please follow these steps:

1.  **Download the Project**: Obtain the complete source code by downloading the project's `.zip` file from the repository.
2.  **Database Setup**: Download the provided **SQL file** and import it into your **MySQL** database to ensure all necessary tables and initial data are set up correctly.
3.  **Environment Configuration**: Configure your `.env` file with your database credentials and other required settings (e.g., `APP_URL`).
4.  **Install Dependencies**: Navigate to the project directory in your terminal and run `composer install` to install all PHP dependencies.
5.  **Run Migrations & Seeders**: Execute `php artisan migrate --seed` (if applicable) to ensure your database schema is up-to-date and populated with any default data.
6.  **Serve the Application**: Start the local development server by running `php artisan serve`.
