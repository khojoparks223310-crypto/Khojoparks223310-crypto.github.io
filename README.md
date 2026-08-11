index.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Francis Yeboah Asare | Cyber Security Student</title>

    <meta name="description"
          content="Francis Yeboah Asare - Cyber Security student and aspiring cybersecurity professional. Explore my projects, skills, education and professional journey.">

    <meta name="author" content="Francis Yeboah Asare">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            scroll-behavior: smooth;
        }

        body {
            font-family: Arial, Helvetica, sans-serif;
            background: #07111f;
            color: #f5f7fa;
            line-height: 1.6;
        }

        header {
            position: fixed;
            top: 0;
            width: 100%;
            z-index: 1000;
            background: rgba(7, 17, 31, 0.95);
            border-bottom: 1px solid #19304a;
        }

        nav {
            max-width: 1100px;
            margin: auto;
            padding: 18px 25px;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 22px;
            font-weight: bold;
        }

        .logo span {
            color: #00e5ff;
        }

        nav ul {
            display: flex;
            list-style: none;
            gap: 22px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-size: 14px;
        }

        nav a:hover {
            color: #00e5ff;
        }

        .hero {
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 120px 25px 60px;
            background:
                radial-gradient(circle at center, #102b45 0%, #07111f 55%);
        }

        .hero h1 {
            font-size: clamp(42px, 8vw, 78px);
            margin-bottom: 15px;
        }

        .hero h1 span {
            color: #00e5ff;
        }

        .hero h2 {
            font-size: clamp(20px, 4vw, 30px);
            font-weight: normal;
            color: #b7c4d3;
            margin-bottom: 20px;
        }

        .hero p {
            max-width: 700px;
            margin: auto;
            color: #9eafc2;
            font-size: 18px;
        }

        .buttons {
            margin-top: 30px;
        }

        .btn {
            display: inline-block;
            padding: 13px 24px;
            margin: 6px;
            border-radius: 8px;
            text-decoration: none;
            font-weight: bold;
            border: 1px solid #00e5ff;
            color: #00e5ff;
        }

        .btn.primary {
            background: #00e5ff;
            color: #07111f;
        }

        section {
            max-width: 1100px;
            margin: auto;
            padding: 90px 25px;
        }

        .section-title {
            font-size: 36px;
            margin-bottom: 35px;
            color: #00e5ff;
        }

        .about p {
            max-width: 800px;
            color: #b7c4d3;
            font-size: 17px;
        }

        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 15px;
        }

        .skill {
            padding: 22px;
            background: #0d1c2d;
            border: 1px solid #193b58;
            border-radius: 10px;
            text-align: center;
        }

        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .project {
            background: #0d1c2d;
            padding: 25px;
            border-radius: 12px;
            border: 1px solid #193b58;
        }

        .project h3 {
            margin-bottom: 10px;
            color: #00e5ff;
        }

        .project p {
            color: #aebdcd;
        }

        .contact {
            text-align: center;
        }

        .contact p {
            color: #b7c4d3;
            margin-bottom: 20px;
        }

        footer {
            text-align: center;
            padding: 30px 20px;
            border-top: 1px solid #19304a;
            color: #8092a7;
        }

        @media (max-width: 700px) {
            nav ul {
                display: none;
            }

            .hero h1 {
                font-size: 45px;
            }

            section {
                padding: 70px 20px;
            }
        }
    </style>
</head>

<body>

<header>
    <nav>
        <div class="logo">Francis<span>.</span></div>

        <ul>
            <li><a href="#about">About</a></li>
            <li><a href="#skills">Skills</a></li>
            <li><a href="#projects">Projects</a></li>
            <li><a href="#education">Education</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
</header>

<section class="hero">
    <div>
        <h1>Francis <span>Yeboah Asare</span></h1>

        <h2>Cyber Security Student | Aspiring Cybersecurity Professional</h2>

        <p>
            Welcome to my personal website. This is where I share my
            cybersecurity journey, projects, skills, learning experiences
            and professional development.
        </p>

        <div class="buttons">
            <a href="#about" class="btn primary">About Me</a>
            <a href="#projects" class="btn">View Projects</a>
        </div>
    </div>
</section>

<section id="about" class="about">
    <h2 class="section-title">About Me</h2>

    <p>
        My name is Francis Yeboah Asare. I am a Cyber Security student
        with a growing interest in technology, cybersecurity, programming
        and digital security.
    </p>

    <br>

    <p>
        I am currently developing my knowledge and practical skills in
        cybersecurity and programming. I use this website to document my
        learning journey, projects and future achievements.
    </p>
</section>

<section id="skills">
    <h2 class="section-title">Cybersecurity Skills</h2>

    <div class="skills">

        <div class="skill">Cybersecurity Fundamentals</div>

        <div class="skill">C++ Programming</div>

        <div class="skill">Computer Networking</div>

        <div class="skill">Linux Fundamentals</div>

        <div class="skill">Web Technologies</div>

        <div class="skill">Problem Solving</div>

    </div>
</section>

<section id="projects">
    <h2 class="section-title">Projects</h2>

    <div class="projects">

        <div class="project">
            <h3>C++ Programming Projects</h3>
            <p>
                Programming exercises and projects created while learning
                C++ and developing problem-solving skills.
            </p>
        </div>

        <div class="project">
            <h3>Cybersecurity Learning</h3>
            <p>
                My ongoing cybersecurity learning journey, including
                security concepts, networking and practical exercises.
            </p>
        </div>

        <div class="project">
            <h3>Personal Portfolio</h3>
            <p>
                This website is a personal project designed to document
                my professional and academic journey.
            </p>
        </div>

    </div>
</section>

<section id="education">
    <h2 class="section-title">Education</h2>

    <p>
        <strong>Cyber Security Student</strong>
    </p>

    <p style="color:#aebdcd;">
        Currently developing knowledge and practical skills in
        cybersecurity, programming and information technology.
    </p>
</section>

<section id="contact" class="contact">
    <h2 class="section-title">Let's Connect</h2>

    <p>
        You can find my professional work and future projects online.
    </p>

    <div class="buttons">

        <a class="btn"
           href="https://github.com/Khojoparks223310-crypto"
           target="_blank">
            GitHub
        </a>

        <!-- Replace this with your LinkedIn profile -->
        <a class="btn"
           href="#"
           target="_blank">
            LinkedIn
        </a>

    </div>
</section>

<footer>
    © 2026 Francis Yeboah Asare. All Rights Reserved.
</footer>

</body>
</html>