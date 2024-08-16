<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ankit Sharma | Portfolio</title>
    <style>
        :root {
            --primary-color: #333;
            --secondary-color: #666;
            --accent-color: #007bff;
            --background-color: #f9f9f9;
            --font-family: 'Arial, sans-serif';
        }

        body {
            font-family: var(--font-family);
            color: var(--primary-color);
            background-color: var(--background-color);
            margin: 0;
            padding: 0;
        }

        header {
            background-color: var(--accent-color);
            padding: 1rem;
        }

        nav h1 {
            display: inline;
            color: white;
        }

        nav ul {
            list-style: none;
            float: right;
        }

        nav ul li {
            display: inline;
            margin-left: 2rem;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
        }

        section {
            padding: 2rem;
        }

        #projects .project-grid {
            display: flex;
            gap: 1rem;
        }

        footer {
            background-color: var(--secondary-color);
            color: white;
            text-align: center;
            padding: 1rem;
            margin-top: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <h1><a href="#">Ankit Sharma</a></h1>
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#skills">Skills</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>
    
    <section id="about">
        <h2>About Me</h2>
        <p>Hi there, I'm Ankit Sharma, a Software Developer at Softage Information Technology.</p>
    </section>
    
    <section id="skills">
        <h2>Skills</h2>
        <ul>
            <li>HTML, CSS, JavaScript, ReactJS</li>
            <li>C#, ASP.NET MVC, ASP.NET Core, Web API</li>
            <li>SQL, MySQL, Python</li>    
        </ul>
    </section>
    
    <section id="projects">
        <h2>Projects</h2>
        <div class="project-grid">
            <!-- Add project cards here -->
        </div>
    </section>
    
    <section id="contact">
        <h2>Contact</h2>
        <p>📫 Email me at <a href="mailto:71704@gmail.com">71704@gmail.com</a></p>
    </section>
    
    <footer>
        <p>Connect with me on <a href="https://www.linkedin.com/in/ankit-sharma-06427b1a1/">LinkedIn</a> | <a href="https://github.com/ankitvip">GitHub</a></p>
    </footer>
</body>
</html>
