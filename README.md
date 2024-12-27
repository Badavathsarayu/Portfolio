#portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio - Badavath Sarayu Naik</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
            color: #333;
        }

        header {
            text-align: center;
            padding: 20px;
            background-color: #e3f2fd; /* Light blue header */
            position: relative; /* Added to position elements inside */
        }

        .header-container {
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .header-text {
            text-align: left;
        }

        header h1 {
            font-size: 2.5rem;
            margin: 0;
            color: #1e88e5; /* Blue text */
        }

        header p {
            font-size: 1.2rem;
            color: #d32f2f; /* Red subtext */
        }

        .profile-photo {
            width: 120px; /* Adjust size as needed */
            height: 120px;
            border-radius: 50%;
            position: absolute;
            right: 20px; /* Align photo to the right */
            top: 50%; /* Center vertically */
            transform: translateY(-50%); /* Adjust to perfectly center the photo */
        }

        .button {
            text-decoration: none;
            color: #fff;
            background-color: #1e88e5;
            padding: 10px 20px;
            border-radius: 5px;
            display: inline-block;
            margin: 10px 5px;
            font-weight: bold;
        }

        .button:hover {
            background-color: #1565c0;
        }

        nav {
            display: flex;
            justify-content: center;
            background-color: #2e2a2a;
            padding: 10px 0;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #cbd9e4;
            font-weight: bold;
        }

        nav a:hover {
            color: #77a9d1;
        }

        section {
            padding: 20px;
        }

        .experience, .skills, .projects {
            margin: 20px auto;
            max-width: 800px;
            border: 1px solid #1e88e5;
            border-radius: 8px;
            padding: 20px;
            background-color: #e3f2fd;
        }

        .experience h2, .skills h2, .projects h2 {
            border-bottom: 2px solid #d32f2f;
            padding-bottom: 5px;
            margin-bottom: 15px;
            color: #d32f2f;
        }

        .experience ul, .skills ul {
            list-style: none;
            padding: 0;
        }

        .experience ul li, .skills ul li {
            margin: 10px 0;
        }

        .skills img {
            width: 50px;
            margin: 10px;
        }

        .projects img {
            width: 100%;
            border-radius: 8px;
            margin-bottom: 15px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #e3f2fd;
            color: #d32f2f;
        }

        footer h2 {
            font-size: 1.5rem;
            margin-bottom: 15px;
            color: #1e88e5;
        }

        .social-icons {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 10px;
        }

        .social-icons a {
            text-decoration: none;
            color: inherit;
        }

        .social-icons img {
            width: 60px;
            height: 100px;
        }
    </style>
</head>
<body>

<header>
    <div class="header-container">
        <div class="header-text">
            <h1>Badavath Sarayu Naik</h1>
            <p>And I'm good at <strong>web design</strong></p>
        </div>
        <img src="https://1drv.ms/i/c/5a828dfbdb788930/UQQwiXjb-42CIIBawgAAAAAAAGItYf2e5XXoRG0?width=1024" alt="Badavath Sarayu Naik" class="profile-photo">
    </div>
    <a href="#" class="button">Download Resume</a>
</header>

<nav>
    <a href="#about-me">About Me</a>
    <a href="#projects">Projects</a>
    <a href="#skills">Skills</a>
    <a href="#connect">Connect</a>
</nav>

<section id="about-me" class="experience">
    <h2>Experience</h2>
    <ul>
        <li>
            <strong>About Me</strong>
            <ul>
                <li>I am Sarayu Badavath, a student at SR University (Batch 2023-2027), pursuing a B.Tech in CSE.</li>
                <li><strong>Internship - Cybersecurity</strong>: I am passionate about leveraging technology to solve real-world problems. I have hands-on experience through internships and projects, including cybersecurity compliance, data privacy, and creating user-friendly web applications. My goal is to continuously learn and contribute to innovative solutions in the tech industry.</li>
            </ul>
        </li>
    </ul>
</section>

<section id="skills" class="skills">
    <h2>Skills</h2>
    <ul>
        <li>
            <strong>Programming Languages:</strong>
            <img src="https://upload.wikimedia.org/wikipedia/commons/1/18/C_Programming_Language.svg" alt="C">
            <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" alt="Python">
        </li>
        <li>
            <strong>Databases:</strong>
            <img src="https://upload.wikimedia.org/wikipedia/commons/2/29/Postgresql_elephant.svg" alt="DBMS">
        </li>
    </ul>
</section>

<section id="projects" class="projects">
    <h2>Projects</h2>
    <div>
        <h3>Bookstore Website</h3>
        <a href="https://badavathsarayu.github.io/Hci_02_UvaBooks/" target="_blank" class="button">View live demo</a>
        <img src="https://1drv.ms/i/c/5a828dfbdb788930/IQT5Hlz9jQI5SKduLZcPr9uhARz7awetIVWUanazBrAAZGQ?width=1024" alt="Bookstore Website">
        <p>
            The Bookstore Website offers a seamless and personalized platform for readers to explore, discover, and purchase books, catering to diverse literary tastes with an extensive collection and user-friendly features. From timeless classics to the latest bestsellers, the website ensures a rich and diverse catalog for every reader. With secure payment options and efficient delivery services, it provides a hassle-free shopping experience for book lovers everywhere.
        </p>
        <p><strong>Technology Stack:</strong></p>
        <ul>
            <li>Programming Languages: Python, C</li>
            <li>IDE: HTML, CSS</li>
            <li>Database: DBMS</li>
        </ul>
    </div>
</section>

<footer id="connect">
    <h2>Connect with Me</h2>
    <div class="social-icons">
        <a href="https://github.com/Badavathsarayu/Hci_02_UvaBooks.git" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" alt="GitHub"></a>
        <a href="https://wa.me/1234567890" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp"></a>
        <a href="mailto:sarayubadavath@gmail.com" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Gmail_Icon.png" alt="Gmail"></a>
        <a href="https://www.linkedin.com/in/badavath-sarayu-81b35b300" target="_blank">
            <img src="https://upload.wikimedia.org/wikipedia/commons/8/81/LinkedIn_icon.svg" alt="LinkedIn">
        </a>
    </div>
    <p>&copy; 2024 Badavath Sarayu Naik</p>
</footer>

</body>
</html>
