<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sarvesh S Ravaloji | Portfolio</title>
    <style>
        :root {
            --bg: #0f172a;
            --card-bg: #1e293b;
            --text-main: #f8fafc;
            --accent: #38bdf8;
            --text-dim: #94a3b8;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg);
            color: var(--text-main);
            line-height: 1.6;
            margin: 0;
            padding: 0;
        }

        header {
            text-align: center;
            padding: 4rem 2rem;
            background: linear-gradient(to bottom, #1e293b, var(--bg));
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 0 20px;
        }

        h1 { font-size: 2.5rem; margin-bottom: 0.5rem; color: var(--accent); }
        .contact-info { color: var(--text-dim); margin-bottom: 2rem; }
        
        section { margin-bottom: 3rem; }
        h2 { border-bottom: 2px solid var(--accent); display: inline-block; padding-bottom: 5px; }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 1.5rem;
        }

        .card {
            background: var(--card-bg);
            padding: 1.5rem;
            border-radius: 8px;
            transition: transform 0.3s;
        }

        .card:hover { transform: translateY(-5px); }

        .skill-tag {
            display: inline-block;
            background: #334155;
            color: var(--accent);
            padding: 5px 12px;
            border-radius: 20px;
            margin: 5px;
            font-size: 0.9rem;
        }

        footer { text-align: center; padding: 2rem; color: var(--text-dim); font-size: 0.8rem; }
    </style>
</head>
<body>

<header>
    <div class="container">
        <h1>SARVESH S RAVALOJI </h1>
        <p class="contact-info">
            Belagavi, Karnataka  | 8971074703 | shankarsarvesh63@gmail.com
        </p>
        <p><em>Motivated BCA graduate seeking an entry-level IT role to contribute to innovative projects.</em></p>
    </div>
</header>

<div class="container">
    <section id="experience">
        <h2>Experience & Education</h2>
        <div class="card">
            <h3>Web Applications Development Intern </h3>
            <p><strong>Infynow Software Solutions LLP</strong> (3 Months)</p>
        </div>
        <div style="margin-top: 1rem;" class="card">
            <h3>Bachelor of Computer Applications (BCA) </h3>
            <p><strong>Govindram Sekskeria College</strong> (2021-2025) </p>
        </div>
    </section>

    <section id="projects">
        <h2>Academic Projects</h2>
        <div class="card">
            <h3>Train Food Order Management System </h3>
            <p>Designed a user-friendly interface and managed relational databases to streamline food delivery in trains. </p>
            <p><strong>Tech:</strong> Java, MySQL, JavaScript, HTML, CSS</p>
        </div>
    </section>

    <section id="skills">
        <h2>Technical & Soft Skills</h2>
        <div>
            <span class="skill-tag">Python </span>
            <span class="skill-tag">HTML </span>
            <span class="skill-tag">SQL</span>
            <span class="skill-tag">MySQL </span>
            <span class="skill-tag">Java </span>
            <span class="skill-tag">Team Work </span>
            <span class="skill-tag">Adaptability</span>
            <span class="skill-tag">Adobe/CapCut </span>
        </div>
    </section>
</div>

<footer>
    <p>&copy; 2026 Sarvesh S Ravaloji. Built with HTML/CSS.</p>
</footer>

</body>
</html>
