#Radiant Salon 

Radiant Salon is a modern and elegant beauty salon website designed mainly for marketing and advertising purposes. It allows users to explore available beauty services and submit an appointment interest request, which is later handled manually by the salon.

#Description

Radiant Salon showcases a variety of professional beauty services such as haircuts, styling, makeup, and spa treatments. The website focuses on delivering a visually appealing and user-friendly experience that reflects the luxury and professionalism of the salon.

Users can:

View detailed service information with pricing

Submit an appointment interest form with a preferred date

Explore the salon’s offerings on any device using a responsive design

⚠️ Note: This system does not provide full automated scheduling. Appointment requests are stored in the database and managed internally by the salon.How to Run the Project

Follow these steps to run the project on your local machine:

1.Clone the Repository
git clone https://github.com/noura/beautySalon.git

2️⃣ Move Project to Server Directory

For XAMPP: place the folder inside htdocs

For WAMP: place the folder inside www

3️⃣ Set Up the Database

Open phpMyAdmin

Create a new database (e.g., radiant_salon)

Import the provided .sql file (if included)

4️⃣ Configure Database Connection

Open the PHP configuration file (e.g., config.php)

Update database credentials:

$host = "localhost";
$user = "root";
$password = "";
$database = "radiant_salon";

5️⃣ Run the Project

Start Apache and MySQL

Open your browser

Visit:

http://localhost/beautySalon

🛠 Tech Stack

Frontend: HTML, CSS, JavaScript, Bootstrap

Backend: PHP

Database: MySQL

Server: Apache / Nginx#
