<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Anfal Djahfa Portfolio</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family: Arial, Helvetica, sans-serif;
    }

    body{
      background:#0f172a;
      color:white;
      line-height:1.6;
    }

    .container{
      width:90%;
      max-width:1100px;
      margin:auto;
    }

    header{
      padding:60px 0;
      text-align:center;
    }

    header h1{
      font-size:55px;
      margin-bottom:10px;
      color:#38bdf8;
    }

    header p{
      font-size:20px;
      color:#cbd5e1;
    }

    section{
      margin:50px 0;
    }

    .title{
      font-size:32px;
      margin-bottom:25px;
      color:#38bdf8;
      border-left:5px solid #38bdf8;
      padding-left:15px;
    }

    .about{
      background:#1e293b;
      padding:30px;
      border-radius:15px;
    }

    .skills{
      display:flex;
      flex-wrap:wrap;
      gap:15px;
    }

    .skill{
      background:#38bdf8;
      color:#0f172a;
      padding:12px 20px;
      border-radius:30px;
      font-weight:bold;
    }

    .projects{
      display:grid;
      grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
      gap:20px;
    }

    .card{
      background:#1e293b;
      padding:25px;
      border-radius:15px;
      transition:0.3s;
    }

    .card:hover{
      transform:translateY(-5px);
      background:#334155;
    }

    .card h3{
      margin-bottom:15px;
      color:#38bdf8;
    }

    .contact{
      text-align:center;
    }

    .contact a{
      text-decoration:none;
      color:white;
      background:#38bdf8;
      padding:12px 25px;
      border-radius:30px;
      display:inline-block;
      margin:10px;
      font-weight:bold;
      transition:0.3s;
    }

    .contact a:hover{
      background:#0ea5e9;
    }

    footer{
      text-align:center;
      padding:25px;
      color:#94a3b8;
      margin-top:50px;
    }
  </style>
</head>
<body>

  <div class="container">

 <header>
      <h1>Anfal Jahfa</h1>
      <p>Web Developer • UI/UX Designer • IT Student</p>
    </header>

  <section>
      <h2 class="title">About Me</h2>

<div class="about">
        <p>
          Hello 👋 I'm <strong>Anfal Jahfa</strong>, a third-year Information Technology student from Algeria.
          I am passionate about Frontend and Backend development, UI/UX design, and building creative digital projects.
        </p>

<br>

 <p>
          Currently learning React and Mobile Development.  
          I also build Discord bots and responsive web applications.
        </p>

 <br>

 <p>
          Natural leader, passionate to learn and improve every day 🚀
        </p>
      </div>
    </section>

 <section>
      <h2 class="title">Skills</h2>

<div class="skills">
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JavaScript</div>
        <div class="skill">PHP</div>
        <div class="skill">Java</div>
        <div class="skill">React</div>
        <div class="skill">Git</div>
        <div class="skill">UI/UX</div>
        <div class="skill">Figma</div>
        <div class="skill">Discord Bots</div>
      </div>
    </section>

<section>
      <h2 class="title">Projects</h2>

<div class="projects">

<div class="card">
          <h3>Discord Bots</h3>
          <p>
            Built Discord bots using JavaScript and Node.js with commands and AI integrations.
          </p>
        </div>

<div class="card">
          <h3>Web Applications</h3>
          <p>
            Developed responsive and modern websites using HTML, CSS, JavaScript and PHP.
          </p>
        </div>

  <div class="card">
          <h3>UI/UX Design</h3>
          <p>
            Designed user-friendly interfaces and prototypes using Figma.
          </p>
        </div>

 </div>
    </section>

<section class="contact">
      <h2 class="title">Contact Me</h2>

 <a href="https://github.com/AnfalDjahfa">GitHub</a>
      <a href="www.linkedin.com/in/anfal-djahfa-3179b8410">LinkedIn</a>
      <a href="https://discord.com/users/1005246212498280499">Discord</a>
    </section>

 <footer>
      © 2026 Anfal Djahfa• All Rights Reserved
    </footer>

  </div>

</body>
</html>
