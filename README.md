
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - [Your Name]</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 1rem 0;
            text-align: center;
        }

        nav {
            margin: 0 auto;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 1rem;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 2rem;
            max-width: 900px;
            margin: 0 auto;
        }

        .skills, .projects {
            margin-top: 2rem;
        }

        .projects ul, .skills ul {
            list-style-type: none;
            padding: 0;
        }

        .projects li, .skills li {
            background: #fff;
            padding: 1rem;
            margin: 0.5rem 0;
            border-radius: 5px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        a {
            color: #007acc;
        }

        a:hover {
            text-decoration: none;
        }
    </style>
</head>

<body>
    <header>
        <h1>[Your Name]</h1>
        <nav>
            <a href="#about">About Me</a>
            <a href="#skills">Skills</a>
            <a href="#projects">Projects</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <section id="about">
        <h2>About Me</h2>
        <p>Hello! I am [Your Name], a Computer Engineering student at The University of Texas at San Antonio. I specialize in embedded systems, FPGA programming, and Android development. I am passionate about creating efficient solutions for real-world problems.</p>
    </section>

    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li><strong>Programming Languages:</strong> C, C++, Java, Python, Verilog, HTML, CSS</li>
            <li><strong>Tools:</strong> Vivado, Logisim, IntelliJ, Visual Studio Code, Linux</li>
            <li><strong>Relevant Areas:</strong> Embedded Systems, FPGA Programming, Machine Learning Basics</li>
        </ul>
    </section>

    <section id="projects">
        <h2>Projects</h2>
        <ul>
            <li>
                <strong>Card Key Reader Simulation:</strong> Developed logic for a secure card key reader using Logisim.
            </li>
            <li>
                <strong>FPGA Alarm Clock:</strong> Designed an alarm clock on a Nexys 7 FPGA using 7-segment displays and Verilog.
            </li>
            <li>
                <strong>Android App for Light Therapy:</strong> Developing an Android app with Bluetooth integration to address Seasonal Affective Disorder (SAD).
            </li>
            <li>
                <strong>FPGA Ping Pong Game:</strong> Implemented a simple ping pong game on an FPGA using Verilog.
            </li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact</h2>
        <p>You can reach me via email at <a href="mailto:yourname@example.com">yourname@example.com</a> or visit my <a href="https://github.com/yourgithub" target="_blank">GitHub</a> profile for more projects.</p>
    </section>

    <footer>
        <p>&copy; 2024 [Your Name]. All rights reserved.</p>
    </footer>
</body>

</html>
