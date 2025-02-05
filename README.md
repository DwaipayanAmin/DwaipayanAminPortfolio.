<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dwaipayan Amin | Portfolio</title>
    <!-- Font Awesome for Social Media Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            animation: fadeIn 2s ease-in-out;
        }

        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }

        header {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
            animation: slideIn 1.5s ease-out;
        }

        @keyframes slideIn {
            from { transform: translateY(-100%); }
            to { transform: translateY(0); }
        }

        nav {
            background: #444;
            padding: 10px;
            text-align: center;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #00bcd4;
        }

        section {
            padding: 20px;
            animation: fadeUp 1s ease-in;
            text-align: center;
        }

        @keyframes fadeUp {
            from { transform: translateY(20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }

        ul {
            list-style: none;
            padding: 0;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px 0;
        }

        /* Profile Picture Styling */
        .profile-pic {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 3px solid #00bcd4;
            margin-top: 20px;
            transition: transform 0.3s ease;
        }

        .profile-pic:hover {
            transform: scale(1.1);
        }

        /* Social Media Icons */
        .social-icons {
            text-align: center;
            margin: 20px 0;
        }

        .social-icons a {
            color: #444;
            font-size: 24px;
            margin: 0 10px;
            transition: transform 0.3s, color 0.3s;
        }

        .social-icons a:hover {
            color: #00bcd4;
            transform: scale(1.2);
        }
    </style>
</head>
<body>

<header>
    <h1>Dwaipayan Amin</h1>
    <p>Arts Student | DFA Certified | Gamer</p>
    <!-- Profile Picture -->
    <img src="profile.jpg" alt="Dwaipayan Amin" class="profile-pic">
</header>

<nav>
    <a href="#about">About Me</a>
    <a href="#education">Education</a>
    <a href="#skills">Skills</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <h2>About Me</h2>
    <p>Hello! I'm Dwaipayan Amin from Bhatar, West Bengal. I'm an Arts student with a DFA certification, passionate about gaming, and eager to build a career in companies like TCS or Reliance.</p>
</section>

<section id="education">
    <h2>Education</h2>
    <ul>
        <li>Palar Bhatar F.P School</li>
        <li>Bhatar Madhab Public High School (HS)</li>
        <li>DFA - Bhatar Jawaharlal Nehru Computer Literacy Drive</li>
    </ul>
</section>

<section id="skills">
    <h2>Skills</h2>
    <ul>
        <li>Computer Proficiency (DFA Certified)</li>
        <li>Arts & Humanities Knowledge</li>
        <li>Free Fire Gaming Expertise</li>
    </ul>
</section>

<section id="contact">
    <h2>Contact Me</h2>
    <p>Email: <a href="mailto:dwaipayanamin@outlook.com">dwaipayanamin@outlook.com</a></p>
    <p>Phone: <a href="tel:+916294686653">+91 62946 86653</a></p>

    <!-- Social Media Links -->
    <div class="social-icons">
        <a href="https://www.facebook.com" target="_blank"><i class="fab fa-facebook"></i></a>
        <a href="https://www.instagram.com" target="_blank"><i class="fab fa-instagram"></i></a>
        <a href="https://www.linkedin.com" target="_blank"><i class="fab fa-linkedin"></i></a>
        <a href="https://www.github.com" target="_blank"><i class="fab fa-github"></i></a>
    </div>
</section>

<footer>
    <p>© 2025 Dwaipayan Amin | All Rights Reserved</p>
</footer>

</body>
</html>
