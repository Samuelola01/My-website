<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Samuel Ola - Christian Content Creator</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background: url('https://drive.google.com/file/d/1A6XeT__5SPMqIjUwtO3Vm8hFTHEcLlUV/view?usp=drivesdk') center/cover no-repeat, linear-gradient(45deg, rgba(74, 144, 226, 0.7), rgba(106, 90, 205, 0.7));
            color: white;
            padding: 3em 0;
            text-align: center;
            position: relative;
        }
        header::before {
            content: "";
            background: linear-gradient(45deg, rgba(74, 144, 226, 0.7), rgba(106, 90, 205, 0.7));
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            z-index: 1;
        }
        header h1, header p {
            position: relative;
            z-index: 2;
        }
        header h1 {
            margin: 0;
            font-size: 2.5em;
        }
        header p {
            margin: 0;
            font-size: 1.2em;
        }
        nav {
            background: linear-gradient(45deg, #333, #575757);
            overflow: hidden;
        }
        nav a {
            float: left;
            display: block;
            color: white;
            text-align: center;
            padding: 14px 20px;
            text-decoration: none;
        }
        nav a:hover {
            background: linear-gradient(45deg, #575757, #333);
        }
        .container {
            padding: 2em;
        }
        .section {
            margin-bottom: 2em;
        }
        h2 {
            border-bottom: 2px solid #4a90e2;
            padding-bottom: 0.3em;
            font-size: 2em;
        }
        footer {
            text-align: center;
            padding: 1em 0;
            background: linear-gradient(45deg, #333, #575757);
            color: white;
        }
        @media (max-width: 768px) {
            header h1 {
                font-size: 2em;
            }
            nav a {
                float: none;
                width: 100%;
                text-align: left;
                padding: 10px 15px;
            }
            .container {
                padding: 1em;
            }
            .section {
                margin-bottom: 1.5em;
            }
            h2 {
                font-size: 1.5em;
            }
        }
        @media (max-width: 480px) {
            header {
                padding: 2em 0;
            }
            header h1 {
                font-size: 1.8em;
            }
            nav a {
                padding: 8px 10px;
            }
            .container {
                padding: 0.5em;
            }
            .section {
                margin-bottom: 1em;
            }
            h2 {
                font-size: 1.2em;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Samuel Ola</h1>
        <p>Christian Content Creator & Video Editor</p>
    </header>
    <nav>
        <a href="#about">About Me</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about" class="section">
            <h2>About Me</h2>
            <p>Hello, I'm Samuel Ola, a dedicated Christian content creator and skilled video editor. My passion lies in creating impactful content that shares positive messages and inspires others. I have a deep love for Jesus, a commitment to good character, and a keen interest in bookbinding and music. My expertise in video editing allows me to bring stories to life and engage with audiences meaningfully.</p>
        </section>
        <section id="portfolio" class="section">
            <h2>Portfolio</h2>
            <p>Explore some of my recent projects:</p>
            <ul>
                <li><a href="https://pin.it/22qDvsQCs" target="_blank">Music Visualizers</a></li>
                <li><a href="https://pin.it/5og3z5NuQ" target="_blank">Social Media Reels</a></li>
            </ul>
        </section>
        <section id="contact" class="section">
            <h2>Contact</h2>
            <p>You can reach me via email at <a href="mailto:bellosamuel47@gmail.com">bellosamuel47@gmail.com</a> or contact me on <a href="https://wa.me/2349071653577" target="_blank">WhatsApp</a>.</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 Samuel Ola. All rights reserved.</p>
    </footer>
</body>
</html>
