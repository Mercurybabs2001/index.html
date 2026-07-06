<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Qowam Abdulrasak | Portfolio</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    scroll-behavior:smooth;
    font-family:Arial, Helvetica, sans-serif;
}

body{
    background:#0f172a;
    color:#fff;
}

header{
    background:#111827;
    padding:20px;
    position:sticky;
    top:0;
}

header h1{
    color:#38bdf8;
}

nav{
    margin-top:15px;
}

nav a{
    color:white;
    text-decoration:none;
    margin-right:15px;
    font-weight:bold;
}

nav a:hover{
    color:#38bdf8;
}

.hero{
    text-align:center;
    padding:80px 20px;
}

.hero img{
    width:180px;
    height:180px;
    border-radius:50%;
    border:5px solid #38bdf8;
}

.hero h2{
    margin-top:20px;
    font-size:40px;
}

.hero p{
    margin-top:10px;
    font-size:18px;
}

.btn{
    display:inline-block;
    margin-top:30px;
    background:#38bdf8;
    color:white;
    padding:12px 25px;
    text-decoration:none;
    border-radius:8px;
}

section{
    padding:60px 10%;
}

h2{
    color:#38bdf8;
    margin-bottom:20px;
}

.skills{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
    gap:20px;
}

.card{
    background:#1e293b;
    padding:20px;
    border-radius:10px;
}

.project{
    background:#1e293b;
    padding:20px;
    margin-top:20px;
    border-radius:10px;
}

table{
    width:100%;
    border-collapse:collapse;
}

table,th,td{
    border:1px solid white;
}

th,td{
    padding:10px;
}

input,textarea{
    width:100%;
    padding:12px;
    margin-top:8px;
    margin-bottom:15px;
}

button{
    background:#38bdf8;
    color:white;
    border:none;
    padding:12px 20px;
    border-radius:5px;
}

footer{
    text-align:center;
    background:#111827;
    padding:20px;
}

@media(max-width:700px){
.hero h2{
font-size:30px;
}
}
</style>

</head>

<body>

<header>
<h1>Qowam Abdulrasak</h1>

<nav>
<a href="#about">About</a>
<a href="#skills">Skills</a>
<a href="#projects">Projects</a>
<a href="#education">Education</a>
<a href="#contact">Contact</a>
</nav>

</header>

<section class="hero">

<img src="https://via.placeholder.com/180" alt="Profile Photo">

<h2>Hello, I'm Qowam Abdulrasak</h2>

<p>Aspiring Full-Stack Web Developer</p>

<a href="#" class="btn">Download CV</a>

</section>

<section id="about">

<h2>About Me</h2>

<p>
I am a Computer Science student at Lens University.
I love building websites, learning programming,
and solving real-world problems with technology.
My dream is to become a professional Full-Stack Web Developer.
</p>

</section>

<section id="skills">

<h2>Skills</h2>

<div class="skills">

<div class="card">
<h3>HTML</h3>
<p>★★★★★</p>
</div>

<div class="card">
<h3>CSS</h3>
<p>★★★★☆</p>
</div>

<div class="card">
<h3>JavaScript</h3>
<p>Learning...</p>
</div>

<div class="card">
<h3>Python</h3>
<p>★★★★☆</p>
</div>

<div class="card">
<h3>Web Design</h3>
<p>★★★★☆</p>
</div>

<div class="card">
<h3>Problem Solving</h3>
<p>★★★★★</p>
</div>

</div>

</section>

<section id="projects">

<h2>Projects</h2>

<div class="project">
<h3>Personal Biography Website</h3>
<p>Built with HTML.</p>
</div>

<div class="project">
<h3>Portfolio Website</h3>
<p>Responsive portfolio built using HTML and CSS.</p>
</div>

<div class="project">
<h3>Future Projects</h3>
<p>More exciting projects coming soon.</p>
</div>

</section>

<section id="education">

<h2>Education</h2>

<table>

<tr>

<th>Institution</th>

<th>Course</th>

<th>Status</th>

</tr>

<tr>

<td>Lens University</td>

<td>Computer Science</td>

<td>Student</td>

</tr>

</table>

</section>

<section id="contact">

<h2>Contact Me</h2>

<p>Email: your@email.com</p>

<p>Phone: +234 XXX XXX XXXX</p>

<form>

<input type="text" placeholder="Your Name">

<input type="email" placeholder="Your Email">

<textarea rows="6" placeholder="Your Message"></textarea>

<button>Send Message</button>

</form>

</section>

<footer>

<p>© 2026 Qowam Abdulrasak | All Rights Reserved.</p>

</footer>

</body>
</html>
