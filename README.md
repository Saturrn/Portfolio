<html>
<head>
<style>
{
  background-color: #2DC4A8;
}
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: black;
  position: fixed;
  top: 0;
  width: 100%;
}

li {
  float: left;
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
  background-color: #2DC4A8;
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
    <li><a href="#about">About</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</div>


<div id="navbar">
  <ul>
    <li><a href="#welcome-section">Home</a></li>
    <li><a href="#projects">Projects</a></li>
    <li><a href="https://github.com/Saturrn" target="_blank">Github</a>       </li>
    <li><a href="#about">About</a></li>
    <li><a href="#contact">Contact</a></li>
  </ul>
</div>

<div class="Welcome">
<section id="welcome-section">
  <h1> Atahan's Portfolio</h1>
</section>
</div>

<section id="welcome-section">
  <div class="welcome-section">
    <h2> Welcome to my website </h2>
    <p> Student web developer </p>
  </div>
  </section>
<section id="projects">
  <div class="project-tile">
    <h2> Intern </h2>
    <p> Shitty HTML developer </p>
  </div>
  </section>
  
 <section id="about">
  <div class="About">
    <h2> About me </h2>
    <p> I am a student at Kuben Vocational arena where I study computers and electronics </p>
    <p>My goal with this website is to display my skills with web coding etc </p>
  </div>
  </section>

<section id="contact">
  <div class="contact">
    <h2> Contact </h2>
   <a href="https://www.twitter.com" target="_blank">
<img border="0" alt="Twitter" src="https://norsis.no/wp-content/uploads/2018/05/twitter.jpg" width="50" height="50">
   <a href="https://www.youtube.com" target="_blank">
<img border="0" alt="Twitter" src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Youtube%28amin%29.png" width="50" height="50">
     <p> Email: Bastas.Atahan@gmail.com </p>
  </div>
  </section>
<script>
document.getElementsByTagName("h1")[0].style.fontSize = "80px";
</script>

</body>
</html>
