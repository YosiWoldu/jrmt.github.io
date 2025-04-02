<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Blair Math Competition</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#registration">Registration</a></li>
                <li><a href="#problems">Past Problems</a></li>
                <li><a href="#sponsors">Sponsors</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Home Section -->
    <section id="home">
        <h1>Welcome to the Blair Math Competition</h1>
        <p>Welcome to our annual math competition, designed to challenge students and foster a love for mathematics!</p>
    </section>

    <!-- About Section -->
    <section id="about">
        <h2>About the Competition</h2>
        <p>This competition brings together students from all over to solve challenging math problems in a fun and competitive environment.</p>
    </section>

    <!-- Registration Section -->
    <section id="registration">
        <h2>Register Now</h2>
        <form action="/submit_registration" method="post">
            <label for="name">Full Name:</label>
            <input type="text" id="name" name="name" required><br>

            <label for="email">Email Address:</label>
            <input type="email" id="email" name="email" required><br>

            <label for="school">School:</label>
            <input type="text" id="school" name="school" required><br>

            <button type="submit">Submit Registration</button>
        </form>
    </section>

    <!-- Past Problems Section -->
    <section id="problems">
        <h2>Past Problems</h2>
        <ul>
            <li><a href="problems/2023.pdf" target="_blank">2023 Problems</a></li>
            <li><a href="problems/2022.pdf" target="_blank">2022 Problems</a></li>
            <li><a href="problems/2021.pdf" target="_blank">2021 Problems</a></li>
        </ul>
    </section>

    <!-- Sponsors Section -->
    <section id="sponsors">
        <h2>Our Sponsors</h2>
        <p>We are grateful for the support of our sponsors:</p>
        <ul>
            <li>Sponsor 1</li>
            <li>Sponsor 2</li>
            <li>Sponsor 3</li>
        </ul>
    </section>

    <!-- Contact Section -->
    <section id="contact">
        <h2>Contact Us</h2>
        <p>Email: info@blairmathcompetition.com</p>
    </section>

    <footer>
        <p>&copy; 2025 Blair Math Competition</p>
    </footer>

    <script src="scripts.js"></script>
</body>
</html>
