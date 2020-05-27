<!DOCTYPE html>
<html>
<head>
<style>
body {
  background-color: #2DC4A8;
}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: black;
}

li {
  float: left;
  border-right:1px solid #bbb;
}

li:last-child {
  border-right: none;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover:not(.active) {
  background-color: #2DC4A8;
}

.active {
  background-color: #black;
}

#welcome-section {
  background-color: #2DC4A8;
  font-size: 40px;
  color:black;
  padding: 40px;
  text-align: center;
}
.project-tile{
  background-color: black;
  color: white;
  margin: 20px;
  padding: 20px;
}
.contact{
  background-color: black;
  color: white;
  font-size: 30;
  margin: 20px;
  padding: 20px;
}
.About{
  background-color: black;
  color: white;
  font-size: 30;
  margin: 20px;
  padding: 20px;
}
.Welcome{
  height: 100vh;
  text-align: center;
  font-size: 50px;
}

@media only screen and (max-width: 1300px) {
  .project-tile {
    background-color: white;
    color: black;
  }
}
</style>
</head>
<body>

<div id="navbar">
  <ul>
    <li><a href="#welcome-section">Home</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="https://github.com/Saturrn" target="_blank">Github</a>       </li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#about">About</a></li>
  </ul>
</div>

</body>

<div class="Welcome">
<section id="welcome-section">
  <h1> Atahan's Portfolio</h1>
</section>
</div>

<section id="projects">
  <div class="project-tile">
    <h2> Welcome to my portfolio </h2>
    <p> Shitty python developer </p>
  </div>
  </section>
<section id="Projects">
  <div class="project-tile">
    <h2> Intern </h2>
    <p> Shitty HTML developer </p>
  </div>
  </section>
  
 <section id="about">
  <div class="About">
    <h2> About me </h2>
    <p> Phone number: 12 34 5678 </p>
    <p> Email: Bastas@mail.com </p>
  </div>
  </section>

<section id="Contact">
  <div class="contact">
    <h2> Contact </h2>
    <p> This is my project </p>
    <p> This is my project </p>
  </div>
  </section>

<script>
document.getElementsByTagName("h1")[0].style.fontSize = "80px";
</script>

</body>
</html>
