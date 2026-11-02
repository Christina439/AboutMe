# AboutMe 
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>About Christina</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family: Arial, sans-serif;
    background: linear-gradient(135deg, #d8f3dc, #b7e4c7);
    color: #333;
}

/* Header */
header {
    background: white;
    text-align: center;
    padding: 30px 20px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    position: sticky;
    top: 0;
    z-index: 100;
}

header h1 {
    color: #2d6a4f;
    font-size: 3rem;
    margin-bottom: 10px;
}

header p {
    color: #666;
    margin-bottom: 20px;
}

/* Navigation Bar */
.navbar {
    display: flex;
    justify-content: center;
    gap: 15px;
    flex-wrap: wrap;
}

.navbar a {
    text-decoration: none;
    color: white;
    background-color: #40916c;
    padding: 10px 20px;
    border-radius: 30px;
    font-weight: bold;
    transition: all 0.3s ease;
}

.navbar a:hover {
    background-color: #2d6a4f;
    transform: translateY(-3px);
}

/* Full-screen sections */
.section {
    min-height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 50px 20px;
}

/* Cards */
.card {
    width: 90%;
    max-width: 900px;
    padding: 50px;
    border-radius: 25px;
    color: white;
    box-shadow: 0 10px 25px rgba(0,0,0,0.15);
    transition: transform 0.3s ease;
}

.card:hover {
    transform: translateY(-10px);
}

.card h2 {
    font-size: 2.2rem;
    margin-bottom: 20px;
}

.card p,
.card li {
    font-size: 1.1rem;
    line-height: 1.8;
}

/* Card Colors */
.about {
    background: #40916c;
}

.skills {
    background: #52b788;
}

.hobbies {
    background: #74c69d;
}

.contact {
    background: #2d6a4f;
}

/* Skill tags */
.skills-container {
    display: flex;
    flex-wrap: wrap;
    gap: 12px;
    margin-top: 20px;
}

.skill-tag {
    background: rgba(255,255,255,0.2);
    padding: 12px 18px;
    border-radius: 25px;
    font-weight: bold;
}

/* Lists */
ul {
    padding-left: 20px;
}

/* Contact Links */
.contact a {
    color: white;
    text-decoration: none;
}

.contact a:hover {
    text-decoration: underline;
}

/* Animation */
.card {
    animation: fadeUp 0.8s ease;
}

@keyframes fadeUp {
    from {
        opacity: 0;
        transform: translateY(40px);
    }
    to {
        opacity: 1;
        transform: translateY(0);
    }
}

/* Footer */
footer {
    text-align: center;
    padding: 25px;
    color: #2d6a4f;
    font-weight: bold;
}
</style>
</head>
<body>

<header>
    <h1>Christina Radoor</h1>
    <p>🎓 Student • 💻 Learner • 🌱 Creator</p>

    <nav class="navbar">
        #aboutAbout Me</a>
        #skillsSkills</a>
        #hobbiesHobbies</a>
        #contactContact</a>
    </nav>
</header>

<!-- ABOUT -->
<section id="about" class="section">
    <div class="card about">
        <h2>🌟 About Me</h2>
        <p>
            Hello! I'm Christina, a student with a passion for learning,
            creativity, and technology. I enjoy discovering new skills,
            tackling challenges, and working on exciting projects.
        </p>

        <p style="margin-top:20px;">
            My goal is to continue growing both personally and professionally,
            while developing skills that allow me to make a positive impact.
        </p>
    </div>
</section>

<!-- SKILLS -->
<section id="skills" class="section">
    <div class="card skills">
        <h2>💻 Skills</h2>

        <div class="skills-container">
            <span class="skill-tag">HTML</span>
            <span class="skill-tag">CSS</span>
            <span class="skill-tag">JavaScript</span>
            <span class="skill-tag">Problem Solving</span>
            <span class="skill-tag">Communication</span>
            <span class="skill-tag">Teamwork</span>
        </div>
    </div>
</section>

<!-- HOBBIES -->
<section id="hobbies" class="section">
    <div class="card hobbies">
        <h2>🎨 Hobbies</h2>

        <ul>
            <li>Coding and Web Design</li>
            <li>Reading</li>
            <li>Gaming</li>
            <li>Listening to Music</li>
            <li>Learning New Technologies</li>
        </ul>
    </div>
</section>

<!-- CONTACT -->
<section id="contact" class="section">
    <div class="card contact">
        <h2>📬 Contact Me</h2>

        <p>📧 your.email@example.com</p>
        <br>

        <p>🐙 github.com/yourusername</p>
        <br>

        <p>💼 linkedin.com/in/yourusername</p>
    </div>
</section>

<footer>
    ✨ Thanks for visiting my website! ✨
</footer>

</body>
</html>
