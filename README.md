# codsoft_TASK-1
#HTML code
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <link rel="stylesheet" href="styles.css" />
    <title>ADITHI SHIBU PORTFOLIO</title>
  </head>
  <body>
    <header>
      <h1>ADITHI SHIBU</h1>
      <p>Engineering student | B.E. Information Science</p>
    </header>

    <section id="about">
      <img src="AS_2.png" alt="Adithi Shibu" />
    </section>

    <section id="about1">
      <h2>
        I am interested in technology, learning new skills, have a creative outlook and interest in travelling.
      </h2>
    </section>

    <section id="projects">
      <h2>Projects</h2>
      <div class="project">
        
        <h3>Project 1</h3>
        <p>Designed and coded an IOT based smart street lighting system</p>
      </div>
      <div class="project">
        
        <h3>Project 2</h3>
        <p>
          Literature survey and raspberry pi study and coding.
        </p>
      </div>
    </section>
    <section id="resume">
      <h2>Resume</h2>
      <p><a href="Adithi Shibu RESUME.pdf" download> Download Resume (PDF)</a></p>
    </section>
    <section id="contact">
      <h2>Contact Details</h2>
      <p>Email: shibuadithi@gmail.com</p>
      <p>Phone: 9786533270</p>
    </section>
    <footer>
      <p>&copy; 2023 Adithi Shibu. All rights reserved.</p>
    </footer>
  </body>
</html>
#CSS code
body {
  font-family: Times New Roman, sans-serif;
  margin: 0;
  background-color: rgb(109, 185, 231);
  padding: 0;
}

header {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 20px 0;
}

header h1 {
  margin: 0;
}

#about1 {
  text-align: center;
  padding: 1px 0;
}
#about {
  text-align: center;
  padding: 20px 0;
}

#about img {
  width: 90px;
  border-radius: 30%;
}

#skills {
  text-align: left;
  padding: 10px 0;
}

#skills ul {
  list-style: none;
}

#projects {
  text-align: center;
  padding: 20px 0;
}

.project {
  margin-bottom: 20px;
}

.project img {
  max-width: 100%;
  border-radius: 5px;
}

#resume,
#contact {
  text-align: center;
  padding: 20px 0;
}

#resume a {
  text-decoration: none;
  color: #333;
  border: 1px solid #333;
  padding: 10px 20px;
  border-radius: 5px;
}

footer {
  background-color: #333;
  color: #fff;
  text-align: center;
  padding: 20px 0;
}
