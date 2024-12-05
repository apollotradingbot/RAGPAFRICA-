<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RAGP Africa</title>
    <style>
        /* General Styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #333333;
            line-height: 1.6;
            overflow-x: hidden; /* Prevent horizontal scrolling */
        }

        /* Header */
        header {
            background-color: #ff0000;
            color: #ffffff;
            padding: 1rem 0;
        }

        header .container {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 1rem;
        }

        header h1 {
            margin: 0;
            font-size: 1.5rem;
        }

        header nav {
            display: flex;
            flex-wrap: wrap; /* Ensure responsiveness */
        }

        header nav a {
            background-color: #000000;
            color: #ffffff;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 5px;
            margin-left: 1rem;
            transition: background-color 0.3s ease;
            font-size: 0.9rem;
        }

        header nav a:hover {
            background-color: #ffcccc;
        }

        /* Sections */
        section {
            padding: 2rem 1rem;
        }

        section .container {
            max-width: 1200px;
            margin: 0 auto;
        }

        h2 {
            color: #ff0000;
            margin-bottom: 1rem;
            font-size: 1.5rem;
        }

        ul {
            list-style-type: disc;
            margin-left: 2rem;
        }

        ul li {
            margin-bottom: 0.5rem;
        }

        /* Video Section */
        .videos iframe {
            width: 100%;
            max-width: 600px;
            height: 350px;
            margin: 1rem 0;
            border: none;
        }

        /* Buttons */
        .buttons {
            margin: 2rem 0;
            text-align: center;
        }

        .buttons a {
            display: inline-block;
            background-color: #000000;
            color: #ffffff;
            text-decoration: none;
            padding: 0.75rem 1.5rem;
            border-radius: 5px;
            margin: 0.5rem;
            transition: background-color 0.3s ease;
            font-size: 0.9rem;
        }

        .buttons a:hover {
            background-color: #ffcccc;
        }

        /* Footer */
        footer {
            background-color: #000000;
            color: #ffffff;
            text-align: center;
            padding: 1rem 0;
            margin-top: 2rem;
        }

        footer a {
            color: #ffcccc;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        /* Media Queries */
        @media (max-width: 768px) {
            header nav a {
                margin-left: 0.5rem;
                padding: 0.5rem;
                font-size: 0.8rem;
            }

            h2 {
                font-size: 1.25rem;
            }

            ul {
                margin-left: 1.5rem;
            }

            .buttons a {
                padding: 0.5rem 1rem;
                font-size: 0.8rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>RAGP Africa</h1>
            <nav>
                <a href="https://wa.link/jjria3" target="_blank">Register</a>
                <a href="#details">More Info</a>
                <a href="#videos">Watch Videos</a>
                <a href="#contact">Contact Us</a>
            </nav>
        </div>
    </header>

    <section class="intro">
        <div class="container">
            <h2>Welcome to RAGP Africa</h2>
            <p>RAGP Africa is a revolutionary platform that empowers individuals to earn a steady income by leveraging the essential telecommunication services we all use daily. By simply connecting people to these services, you can create multiple streams of income and achieve financial freedom.</p>
        </div>
    </section>

    <section class="products" id="details">
        <div class="container">
            <h2>Products and Services</h2>
            <ul>
                <li><strong>Airtime and Data Top-Up:</strong> Earn commissions whenever you or your network purchases airtime or data from any network (MTN, Airtel, Glo, 9Mobile, etc.).</li>
                <li><strong>Electricity Bill Payments:</strong> Help others pay electricity bills conveniently while earning commissions.</li>
                <li><strong>Cable TV Subscriptions:</strong> Simplify payments for DSTV, GOTV, and Startimes while earning.</li>
                <li><strong>WAEC & NECO Result Pins:</strong> Sell pins for exam result checks and earn from every transaction.</li>
                <li><strong>Internet Services:</strong> Enable data sharing and bulk purchases.</li>
                <li><strong>E-commerce Opportunities:</strong> Engage in digital sales and product delivery.</li>
                <li><strong>Other Telecom Services:</strong> Profitable opportunities in the growing telecom industry.</li>
            </ul>
        </div>
    </section>

    <section class="videos" id="videos">
        <div class="container">
            <h2>Watch These Videos</h2>
            <iframe src="https://www.youtube.com/embed/ny1gVv2Ua6o?si=Ou9BWIiuOWbUAzFz" allowfullscreen></iframe>
            <iframe src="https://www.youtube.com/embed/YUghmP1oY8M?feature=shared" allowfullscreen></iframe>
        </div>
    </section>

    <div class="buttons">
        <a href="https://wa.link/jjria3" target="_blank">Get Started</a>
        <a href="#details">Learn More</a>
        <a href="#videos">Watch Videos</a>
    </div>

    <footer id="contact">
        <div class="container">
            <p>&copy; 2024 RAGP Africa. All rights reserved. | <a href="https://wa.link/jjria3">Contact Us</a></p>
        </div>
    </footer>
</body>
</html>
