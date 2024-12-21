<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Italian Restaurant</title>
    <style>
        /* General Styles */
        body {
            font-family: 'Georgia', serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
            color: #333;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        header {
            text-align: center;
            background-color: #d35400;
            color: #fff;
            padding: 20px 0;
        }

        header h1 {
            font-size: 3em;
            margin: 0;
        }

        header p {
            margin: 5px 0 0;
            font-size: 1.2em;
        }

        /* Navigation */
        nav {
            text-align: center;
            margin: 20px 0;
        }

        nav a {
            text-decoration: none;
            color: #d35400;
            margin: 0 15px;
            font-size: 1.2em;
        }

        nav a:hover {
            color: #e74c3c;
        }

        /* About Section */
        .about {
            text-align: center;
            padding: 20px;
        }

        .about h2 {
            font-size: 2em;
            margin-bottom: 10px;
        }

        .about p {
            font-size: 1.2em;
            line-height: 1.6;
        }

        /* Menu Section */
        .menu {
            background-color: #fff;
            padding: 20px;
            margin-top: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .menu h2 {
            text-align: center;
            margin-bottom: 20px;
            font-size: 2em;
            color: #d35400;
        }

        .menu ul {
            list-style: none;
            padding: 0;
        }

        .menu li {
            padding: 10px 0;
            font-size: 1.2em;
            border-bottom: 1px solid #eee;
        }

        .menu li:last-child {
            border-bottom: none;
        }

        /* Reservation Form */
        .reservation {
            background-color: #fff;
            padding: 20px;
            margin-top: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }

        .reservation h2 {
            text-align: center;
            margin-bottom: 20px;
            font-size: 2em;
            color: #d35400;
        }

        .reservation form {
            max-width: 600px;
            margin: 0 auto;
        }

        .reservation label {
            display: block;
            margin-bottom: 5px;
            font-weight: bold;
        }

        .reservation input, .reservation select, .reservation button {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 4px;
            font-size: 1em;
        }

        .reservation button {
            background-color: #d35400;
            color: #fff;
            border: none;
            cursor: pointer;
        }

        .reservation button:hover {
            background-color: #e74c3c;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #333;
            color: #fff;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>CASTLE ITALIO</h1>
        <p>Authentic Italian Cuisine</p>
    </header>

    <nav>
        <a href="#about">About</a>
        <a href="#menu">Menu</a>
        <a href="#reservation">Reserve</a>
        <a href="#contact">Contact</a>
    </nav>

    <div class="container">
        <!-- About Section -->
        <section id="about" class="about">
            <h2>About Us</h2>
            <p>Welcome to CASTLE ITALIO where tradition meets flavor! We bring the heart of Italy to your plate with our authentic recipes and finest ingredients.</p>
        </section>

        <!-- Menu Section -->
        <section id="menu" class="menu">
            <h2>Our Menu</h2>
            <ul>
                <li>Margherita Pizza - $12.99</li>
                <li>Fettuccine Alfredo - $15.99</li>
                <li>Lasagna Bolognese - $14.99</li>
                <li>Spaghetti Carbonara - $13.99</li>
                <li>Tiramisu - $6.99</li>
            </ul>
        </section>

        <!-- Reservation Section -->
        <section id="reservation" class="reservation">
            <h2>Reserve a Table</h2>
            <form action="#" method="post">
                <label for="name">Full Name:</label>
                <input type="text" id="name" name="name" placeholder="Enter your full name" required>

                <label for="email">Email:</label>
                <input type="email" id="email" name="email" placeholder="Enter your email" required>

                <label for="date">Reservation Date:</label>
                <input type="date" id="date" name="date" required>

                <label for="time">Reservation Time:</label>
                <input type="time" id="time" name="time" required>

                <label for="guests">Number of Guests:</label>
                <select id="guests" name="guests" required>
                    <option value="">Select number of guests</option>
                    <option value="1">1</option>
                    <option value="2">2</option>
                    <option value="3">3</option>
                    <option value="4">4</option>
                    <option value="5">5</option>
                    <option value="6+">6+</option>
                </select>

                <button type="submit">Submit Reservation</button>
            </form>
        </section>

        <!-- Contact Section -->
        <section id="contact" class="contact">
            <h2>Contact Us</h2>
            <p>📍 SINDHU BHAVAN,AHEMDABAD/p>
            <p>📞 +91 9978045364</p>
            <p>📧 castleitalio@gmail.com</p>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 CASTLE ITALIO. All rights reserved.</p>
    </footer>
</body>
</html>
