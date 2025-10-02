⭐ Star Rating System using PHP
A simple star rating system built with PHP, MySQL, HTML, CSS, and JavaScript (AJAX).
It allows users to rate items (like products, articles, or movies) and displays the average rating dynamically.

---

📑 Table of Contents

1. Features
2. Project Structure
3. Installation
4. Usage
5. Technologies Used
6. Future Enhancements
7. License

---

🚀 Features
• Users can submit a rating (1 to 5 stars).
• Real-time rating updates using AJAX (no page reload).
• Ratings stored in MySQL database.
• Displays average rating and total votes.
• Prevents duplicate ratings from the same user/IP.

---

📂 Project Structure
star-rating-php/
│── index.php # Main page to display items and ratings
│── rate.php # Handles rating submissions
│── db.php # Database connection file
│── style.css # Styling for the stars
│── script.js # JavaScript for interactive stars
│── README.md # Documentation

---

🛠 Installation

1. Clone the repository:
2. git clone https://github.com/Ashwani4545/Star_rating_using_PHP.git
3. Import database:
   o Create a database star_rating.
   o Create a table rating with required fields.
4. Configure your database in db.php.
5. Run the project in a local server (XAMPP/WAMP/LAMP).

---

🛠️ Setup Instructions

1. Clone or download the project.
2. Create a MySQL database (e.g., star_rating).
3. Create a ratings table with fields for id, item_id, user_ip, rating, and created_at.
4. Update your database connection details in db.php.
5. Open index.php in your browser to test the rating system.

---

📊 How It Works

1. User clicks on a star (1–5).
2. JavaScript sends the rating to the server using AJAX.
3. PHP inserts the rating into the database.
4. The system calculates the average rating and total votes.
5. Updated rating is displayed instantly.

---

▶ Usage
• Open index.php in the browser.
• Click on a star to submit your rating.
• See the average rating and number of votes update instantly.

---

🎨 Technologies Used
• Frontend: HTML, CSS, JavaScript
• Backend: PHP
• Database: MySQL
• AJAX: For real-time updates

---

🔮 Future Enhancements
• ✅ User authentication for personalized ratings.
• ✅ Admin panel to manage ratings.
• ✅ Allow multiple items/products with separate ratings.
• ✅ Support for half-star ratings (★☆).

---

📜 License
This project is licensed under the MIT License.
You can freely use and modify it for your projects.
