<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RAGP Africa</title>
    <style>
        /* General Styles */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa; /* Light Gray */
            color: #333;
        }

        header {
            background-color: #007bff; /* Blue */
            color: white;
            padding: 20px;
            text-align: center;
        }

        h1 {
            margin: 0;
        }

        main {
            padding: 20px;
        }

        h2 {
            color: #007bff;
        }

        ul, ol {
            margin: 10px 0;
            padding-left: 20px;
        }

        .buttons {
            margin-top: 20px;
        }

        button {
            background-color: #007bff; /* Blue */
            color: white;
            padding: 10px 15px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin-right: 10px;
        }

        button:hover {
            background-color: #0056b3; /* Darker Blue */
        }

        footer {
            text-align: center;
            padding: 10px;
            background-color: #f8f9fa; /* Light Gray */
            color: #555;
        }

        footer a {
            color: #007bff;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to RAGP Africa</h1>
    </header>

    <main>
        <section id="about">
            <h2>About RAGP Africa</h2>
            <p>RAGP Africa empowers individuals to earn a steady income by leveraging essential telecommunication services. Build multiple streams of income and achieve financial freedom!</p>
        </section>

        <section id="services">
            <h2>Products and Services</h2>
            <ul>
                <li>Airtime and Data Top-Up</li>
                <li>Electricity Bill Payments</li>
                <li>Cable TV Subscriptions</li>
                <li>WAEC & NECO Result Pins</li>
                <li>Internet Services</li>
                <li>E-commerce Opportunities</li>
            </ul>
        </section>

        <section id="get-started">
            <h2>How to Get Started</h2>
            <p>Follow these simple steps to start earning:</p>
            <ol>
                <li>Click the admin button to get personalized assistance.</li>
                <li>Learn the system and start earning immediately.</li>
                <li>Build your team and watch your income grow.</li>
            </ol>

            <div class="buttons">
                <button onclick="redirectTo('https://wa.link/jjria3')">Register Now</button>
                <button onclick="redirectTo('https://wa.link/jjria3')">Get Info</button>
                <button onclick="redirectTo('https://youtu.be/ny1gVv2Ua6o?si=Ou9BWIiuOWbUAzFz')">Watch Video 1</button>
                <button onclick="redirectTo('https://youtu.be/YUghmP1oY8M?feature=shared')">Watch Video 2</button>
            </div>
        </section>
    </main>

    <footer>
        <p>Contact Admin: <a href="https://wa.link/jjria3">Click Here</a></p>
    </footer>

    <script>
        // JavaScript for user interactions
        function redirectTo(url) {
            window.open(url, '_blank');
        }
    </script>
</body>
</html>
