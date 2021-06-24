<script src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
<style> 
  body{
  background-color: #ff471a;
}
#navbar{
  width: 100%;
  background-color: #1a1a1a;
  overflow:hidden;
  position:fixed;
}
#navbar a{
  float:right;
  position:fixed;
  margin:auto;
  color:#f2f2f2;
  text-align:center;
  padding:16px 20px;
  text-decoration:none;
  font-size:18px;
  transition:background .5s ease, color .5s ease;
}
#navbar a:hover{
  background-color:ff471a;
  color:green;
  position:fixed;
}
#navbar a:active{
  background-color:ff471a;
  color:white;
  position:fixed;
}
#welcome-section{
  height:100vh;
  width:100%;
  display:flex;
  flex-direction:column;
  align-items:center;
  justify-content:center;
  background-image:linear-gradient(to bottom left, #1a1a1a, #333333);
  margin-bottom: 40px;
}
h1 {
  font-size:40px;
  color: white;
}
h2 {
  font-weight:200;
  text-align:center;
  font-size:20px;
  color:#ff471a;
  font-style:italic;
}
div.projects{
  display:flex;
  justify-content:center;
  text-align:center;
  margin-top:100px;
  margin-bottom:100px;
}
.project-tile{
  margin:auto;
  border:none;
  background-color:#1a1a1a;
  text-decoration:none;
  padding:10px;
  width:40px;
  transition:background 1s ease,padding 4s ease;
  cursor:pointer;
  font-size:25px;
  margin:40px;
  
}
.project-tile:hover{
  padding:20px;
  box-shadow:0px 0px 20px #1a1a1a;
}
a:hover{
  text-decoration:none;
  color:#ff471a;
}
a:visited{
  color:#ff471a;
}
a{
  color:#ff471a;
  text-decoration:none;
}
#contact-section{
  height:100vh;
  width:100%;
  display:flex;
  flex-direction:column;
  align-items:center;
  justify-content:center;
  background-image:linear-gradient(to bottom left, #1a1a1a, #333333);
  margin-bottom: 40px;
}
@media screen and (max-width:600px){
  #navbar{position:fixed;
  }
}
</style>

<div class="topnav">
  <nav id="navbar">
    <ul>
      <a id="link1" class="nav-link" href="#welcome-section"> About</a>
      <a id="link1" class="nav-link" href="#projects"> Projects</a>
      <a id="link1" class="nav-link" href="#contact-section"> Contact</a>
    </ul>
  </nav>
</div>
<section id="welcome-section">
  <div class="welcome-text">
    <h1>Welcome text </h1>
    <h2>Steven's portfolio </h2>
  </div>
</section>
<section id="projects">
  <div class="projects">
    <div><a class="project-tile" href="github.com/ander9991" target="_blank">Github</a></div>
    <div><a class="project-tile" href="codepen.io/ander9991" target="_blank">Codepen</a></div>
  </div>
</section>

<section id="contact-section">
  <div class="contact-section" id="contact">
    <h1>Contact Info</h1>
    <h2><a id="profile-link" href="codepen.io/ander9991" target="_blank">Codepen Profile </a></h2>
  </div>
</section>
  
