<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Saranya.N - Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f5f5;
            margin: 0;
            padding: 0;
        }
        .header {
            background-color: #a3d900;
            text-align: center;
            padding: 20px;
            color: white;
            font-size: 24px;
        }
        .navbar {
            background-color: #d60028;
            padding: 10px;
            text-align: center;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            padding: 10px 15px;
            display: inline-block;
        }
        .container {
            max-width: 800px;
            margin: 20px auto;
            background: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        h2 {
            color: #d60028;
        }
        .button {
            background-color: #d60028;
            color: white;
            padding: 10px;
            text-align: center;
            display: block;
            width: 150px;
            margin: 20px auto;
            text-decoration: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <div class="header">
        <h1>Saranya.N</h1>
        <p>BCA Student</p>
    </div>

    <div class="navbar">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#projects">Projects</a>
        <a href="#resume">Resume</a>
    </div>

    <div class="container" id="about">
        <h2>About Me</h2>
        <p>Currently, I am pursuing a BCA degree.</p>
    </div>

    <div class="container" id="education">
        <h2>Education</h2>
        <p>Madras University, BCA</p>
    </div>

    <div class="container" id="skills">
        <h2>Skills</h2>
        <ul>
            <li>Python</li>
            <li>Java</li>
            <li>C++</li>
            <li>Data Structures</li>
        </ul>
    </div>

    <div class="container" id="projects">
        <h2>Projects</h2>
        <ul>
            <li>Adventure game using Java</li>
        </ul>
    </div>

    <div class="container" id="resume">
        <h2>Resume</h2>
        <a href="#" class="button">Download CV</a>
    </div>

    <footer style="text-align:center; padding:20px; background:#222; color:white;">
        © 2024 Saranya.N
    </footer>

</body>
</html>
