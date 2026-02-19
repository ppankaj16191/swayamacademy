<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Swayam Academy</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #f2f6ff;
        }

        header {
            background: linear-gradient(to right, #1e3c72, #2a5298);
            color: white;
            padding: 30px 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 40px;
        }

        nav {
            background-color: #111827;
            padding: 12px;
            text-align: center;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin: 0 20px;
            font-weight: bold;
            font-size: 16px;
        }

        nav a:hover {
            color: #60a5fa;
        }

        section {
            padding: 50px 20px;
            text-align: center;
        }

        .card {
            background: white;
            margin: 20px auto;
            padding: 30px;
            width: 85%;
            max-width: 700px;
            border-radius: 12px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        h2 {
            color: #1e3c72;
        }

        .classes-list p {
            font-size: 18px;
            margin: 8px 0;
        }

        .btn {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 25px;
            background-color: #2563eb;
            color: white;
            text-decoration: none;
            border-radius: 6px;
        }

        .btn:hover {
            background-color: #1e40af;
        }

        footer {
            background-color: #1e3c72;
            color: white;
            padding: 15px;
            text-align: center;
        }

        @media (max-width: 600px) {
            header h1 {
                font-size: 28px;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>Swayam Academy</h1>
    <p>Quality Education for 6th to 10th Standard Students</p>
</header>

<nav>
    <a href="#about">About</a>
    <a href="#classes">Classes</a>
    <a href="#contact">Contact</a>
</nav>

<section id="about">
    <div class="card">
        <h2>About Us</h2>
        <p>
            Swayam Academy provides quality coaching for students of
            6th, 7th, 8th, 9th and 10th standard.
            We focus on strong concept building, exam preparation
            and personal attention for every student.
        </p>
    </div>
</section>

<section id="classes">
    <div class="card">
        <h2>Classes We Offer</h2>
        <div class="classes-list">
            <p>✔ 6th Standard</p>
            <p>✔ 7th Standard</p>
            <p>✔ 8th Standard</p>
            <p>✔ 9th Standard</p>
            <p>✔ 10th Standard</p>
        </div>
    </div>
</section>

<section id="contact">
    <div class="card">
        <h2>Contact Us</h2>
        <p><strong>Address:</strong><br>
        Sant Dnyaneshwar Nagar, Mhasala,<br>
        Wardha - 442001</p>

        <p><strong>Contact Number:</strong><br>
        9665201241</p>

        <a href="tel:9665201241" class="btn">Call Now</a>
    </div>
</section>

<footer>
    © 2026 Swayam Academy | All Rights Reserved
</footer>

</body>
</html>
