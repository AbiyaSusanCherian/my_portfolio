# my_portfolio
MyPortfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Portfolio</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <nav>
      <h1>My Portfolio</h1>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="section">
    <h2>Welcome!</h2>
    <p>Hi,I am Abiya Susan Cherian.</p>
  </section><section id="about" class="section">
    <h2>About Me</h2>
    <p>I am currently pursuing a B.Tech degree in Computer Science. I enjoy learning new technologies, especially web development, programming, and problem-solving.</p>
  </section>

  <section id="skills" class="section">
    <h2>Skills</h2>
    <ul>
      <li>C Programming</li>
      <li>HTML & CSS</li>
      <li>Python </li>
      
    </ul>
  </section>

  <section id="projects" class="section">
    <h2>Projects</h2>
    <div class="project">
<h4>Web Page Design </h4>
<p>Designed a baic webpage using HTML.</p>
      <h4>Student Mark Sheet Table</h4>
      <p>Created a basic student mark sheet using HTML tables.</p>
    </div>
   
  </section>

  <section id="contact" class="section">
    <h2>Contact</h2>
    <p>Email: abiyasuancherian2028@cs.ajce.in</p>
    <p>Phone number:988998890<p>
 
  </section>

 
</body>
</html>
body {
  font-family: sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f0f0f0;
  color: #222;
}

nav {
  background-color: #333;
  color: white;
  padding: 10px;
}

nav h1 {
  margin: 0;
  font-size: 20px;
}

nav ul {
  list-style: none;
  padding: 0;
  margin: 5px 0 0 0;
  display: flex;
  gap: 15px;
}

nav ul li a {
  color: white;
  text-decoration: none;
}

section {
  background-color: white;
  margin: 15px;
  padding: 15px;
  border-radius: 5px;
}

h2 {
  margin-top: 0;
}

footer {
  background-color: #333;
  color: white;
  text-align: center;
  padding: 10px;
}

