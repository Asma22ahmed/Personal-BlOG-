# Personal-BlOG-


Personal Blog Website

HTML CODE :
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="style.css" />
    <link
      rel="stylesheet"
     
    />
    <title>Personal Blog Website</title>
  </head>
  <body>
    <!-- Navbar -->
    <div class="navContainer">
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
    </div>

    <!-- Header -->
    <div class="blueParent" id="about">
      <div class="heroContainer">
        <div class="hero-content">
          <h1>HELLO ! I am Asma, Web Developer</h1>
          <p>
            A third year college student.  Specialist in computer information systems.  Interested in web development.
          </p>
        
      </div>
    </div>

    <!-- skills section -->
    <div class="skillsContainer" id="skills">
      <h1>My Skills</h1>
  
      <div class="skillsItemsContainer">
        <div class="skillItem">
          <p>Html</p>
          <div class="outerdiv">
            <div class="htmldiv"></div>
          </div>
        </div>
        <div class="skillItem">
          <p>css</p>
          <div class="outerdiv">
            <div class="cssdiv"></div>
          </div>
        </div>
        
       
        </div>
      </div>
    </div>

   
    <div class="blueParent" id=" projects">
      <div class="projectsContainer">
        <h1>My projects</h1>
        <div class="projectItemsContainer">
          <div class="project">
            <h3>HTML</h3>
            <p>
              I learned it in college in two Courses
            </p>
            <h4>It was very easy!</h4>
            <span>Html</span>
           
       
          </div>
          <div class="project">
            <h3>CSS</h3>
            <p>
              I learned it outside of college in one course
            </p>
            <h4>It was a bit easy</h4>
           
            <span>css</span>
          
          </div>
        </div>
      </div>
    </div>

    <!-- footer -->
    <div class="footer">
      <div class="socials">
  
        <a href="#"><i class="fab fa-git"></i></a>
      </div>

    </div>
  </body>
</html>



CSS CODE :


html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Roboto", sans-serif;
}

h1 {
  font-size: 56px;
  line-height: 56px;
  color: #c7a2c2;
  margin: 0;
}

h3 {
  font-size: 30px;
  line-height: 36px;
  margin: 0;
}

p {
  font-size: 18px;
  line-height: 26px;
  color: #930c7d;
  margin: 0;
}

.navContainer {
  background: rgba(62, 100, 255, 0.1);
  padding: 20px;
  display: flex;
  justify-content: flex-end;
}

.navContainer a {
  text-decoration: none;
  font-size: 18px;
  margin-right: 50px;
  color: #b8a3bb;
}

.blueParent {
  background: rgba(202, 162, 192, 0.1);
}

.heroContainer {
  display: flex;
  padding: 120px 80px;
  max-width: 1100px;
  margin: auto;
}

.hero-content {
  flex: 2;
}

.hero-content h1 {
  max-width: 500px;
  margin-bottom: 50px;
}
.hero-content p {
  max-width: 500px;
  margin-bottom: 50px;
}

.hero-content a {
  text-decoration: none;
  background: #cb9ecc;
  padding: 17px 32px;
  font-size: 18px;
  color: #bba8bb;
  border-radius: 8px;
}



.skillsContainer {
  padding: 80px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  max-width: 1100px;
  margin: auto;
}

.skillsContainer h1 {
  padding-bottom: 20px;
  border-bottom: 3px solid #a38ca4;
}

.skillsContainer span {
  margin-top: 20px;
}

.skillsItemsContainer {
  display: grid;
  grid-template-columns: repeat(2, auto);
  width: 100%;
  grid-gap: 40px;
}

.skillItem p {
  margin-bottom: 10px;
}



.htmldiv {
  width: 60%;
  height: 20px;
  border-radius: 6px;
  background-color: #c380c9;
}

.cssdiv {
  width: 40%;
  height: 20px;
  border-radius: 6px;
  background-color: #bd6fbe;
}

.gitdiv {
  width: 80%;
  height: 20px;
  border-radius: 6px;
  background-color: #da72be;
}



.projectsContainer {
  padding: 80px;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  max-width: 1100px;
  margin: auto;
}

.projectsContainer h1 {
  padding-bottom: 20px;
  border-bottom: 3px solid #eb89df;
}

.projectItemsContainer {
  padding-top: 50px;
  display: grid;
  grid-template-columns: repeat(2, auto);
  width: 100%;
  grid-gap: 80px;
}

.project {
  border: 3px solid #aa4285;
  padding: 40px;
  background: rgb(225, 153, 213);
  border-radius: 16px;
}

.project p {
  margin-top: 20px;
}

.footer {
  padding: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
.socials {
  margin-bottom: 10px;
}

.fab {
  font-size: 25px;
  color: black;
  margin-right: 20px;
}
Footer

