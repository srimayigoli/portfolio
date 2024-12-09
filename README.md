# portfolio.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <link rel="stylesheet" href="task2.css">
</head>
<body>
    <header>
        <div class="images">
           <img src="C:\Users\golis\Downloads\Businesswoman posing in the city with arms crossed _ Premium AI-generated image.jpg" alt="profile picture">
        </div>
        <div class="name">
            <h1>Goli Srimayi</h1>
            <p>Student</p>
            <nav>
                <ul>
                    <li><a href="#">Welcome to my portfolio! I am a student, eager to learn and grow in the world of [design, web development]. Driven by creativity and curiosity, 
                    i am dedicated to turning ideas into reality while exploring new techniques and pushing boundaries.With the skills and knowledge i've gained from our studies and hands-on projects,and i am strong desire to improve with every project.</a></li>
                    <br>
                    <li><a href="#">I am done with the project which has been conducted in our college[HAVE A PLAN !]and i am exicted to work on new more projects.</a></li>
                    <br>
                    <li><a href="#">We’d love to hear from you! Whether you have a question, want to collaborate on a project, or just want to connect, feel free to reach out.
                        <br>
                        Email: golisrimayi@gmail.com
                    </a></li>
                </ul>
            </nav>
        </div>
    </header>
   <section id="about">
        <h2>About Me</h2>
        <p>Hello! I am Goli Srimayi, a passionate web developer with experience in creating dynamic and responsive websites. I love coding and designing, and I'm constantly looking to learn and improve my skills.</p>
   </section>
    <section id="projects">
        <h2>My Projects</h2>
        <p>I have done with web development project[HAVE A PLAN !]and placed 2nd in my college.</p>
    </section>   
    <section id="contact">
        <h2>Contact Information</h2>
        <p>Email: golisrimayi@gmail.com</p>
        <p>Phone: 7984936783</p>
        <p>LinkedIn: <a href="https://www.linkedin.com/in/srimayi-goli-075a35306?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank">linkedin.com/in/Srimayi Goli</a></p>
    </section> 
    <footer>
        <p> 2024 Goli Srimayi. All rights reserved.</p>
    </footer>
</body>
</html>
# portfolio.css
/* Basic Reset */
body, h1, h2, p, ul {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    background-color: #f4f4f4;
    color: #333;
}

header {
    background-color: grey;
    color: #ffffff;
    text-align: center;
    padding: 2em 0;
}
 .images img {
    border-radius: 50%;
    width: 400px;
    height: 400px;
    margin-bottom: 1em;
}

.name h1 {
    font-size: 40px;
    margin-bottom: 0.5em;
    font-style: italic;
}

.name p {
    font-size: 25px;
    font-weight: 600;
}

nav {
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 1em;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
    font-weight: 500;
    margin-right: 20px;
}

section#about, section#projects, section#contact {
    padding: 2em;
    background-color: #fff;
    margin: 1em 0;
}

section#about h2, section#projects h2, section#contact h2 {
    margin-bottom: 0.5em;
}

footer {
    text-align: center;
    padding: 1em 0;
    background-color: #333;
    color: #fff;
}

/* Responsive Design */
@media (max-width: 768px) {
    nav ul li {
        display: block;
        margin: 0.5em 0;
    }
    header img {
        width: 120px;
        height: 120px;
    }
}

