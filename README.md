<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DevJotaD | Portfólio</title>

  <!-- ICONS -->
  <link rel="stylesheet"
  href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"/>

  <!-- CSS -->
  <link rel="stylesheet" href="style.css">
</head>

<body>

  <!-- FUNDO -->
  <div class="background-animation">
    <span></span>
    <span></span>
    <span></span>
    <span></span>
    <span></span>
  </div>

  <!-- NAVBAR -->
  <header>
    <nav>
      <h1>DevJotaD</h1>

      <ul>
        <li><a href="#home">Início</a></li>
        <li><a href="#sobre">Sobre</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#projects">Projetos</a></li>
        <li><a href="#contact">Contato</a></li>
      </ul>
    </nav>
  </header>

  <!-- HERO -->
  <section class="hero" id="home">

    <div class="hero-text">
      <h2>Olá, eu sou</h2>
      <h1>Jardiel Ryan</h1>

      <h3>Desenvolvedor Full-Stack</h3>

      <p>
        Desenvolvedor focado em apredizado,
        criando interfaces modernas e responsivas e se aprofudando cada dia mais em novos conhecimentos.
      </p>

      <div class="hero-buttons">
        <a href="#projects" class="btn">Ver Projetos</a>
        <a href="https://github.com/DevJotaD" class="btn-outline">GitHub</a>
      </div>
    </div>

    <div class="hero-image">
      <img src="img/logo-jd.png" alt="Perfil">
    </div>

  </section>

  <!-- SOBRE -->
  <section class="about" id="sobre">

    <h2>Sobre Mim</h2>

    <p>
      Sou apaixonado por tecnologia.
      Atualmente estudo HTML, CSS, JavaScript, Php e Banco de Dados, buscando evoluir
      constantemente na área de programação.
    </p>

  </section>

  <!-- SKILLS -->
  <section class="skills" id="skills">

    <h2>Tecnologias</h2>

    <div class="skills-container">

      <div class="skill-card">
        <i class="fa-brands fa-html5"></i>
        <h3>HTML5</h3>
      </div>

      <div class="skill-card">
        <i class="fa-brands fa-css3-alt"></i>
        <h3>CSS3</h3>
      </div>

      <div class="skill-card">
        <i class="fa-brands fa-js"></i>
        <h3>JavaScript</h3>
      </div>

      <div class="skill-card">
        <i class="fa-brands fa-github"></i>
        <h3>GitHub</h3>
      </div>

    </div>

  </section>

  <!-- PROJETOS -->
  <section class="projects" id="projects">

    <h2>Projetos</h2>

    <div class="project-container">

      <a href="#" class="project-card">

        <img src="img/IMG-PORTIFOLIO.png" alt="Projeto">

        <h3>Portfólio Pessoal</h3>

        <p>
          Site moderno desenvolvido utilizando HTML e CSS.
        </p>

      </a>

      <a href="#" class="project-card">

        <img src="https://picsum.photos/401/200" alt="Projeto">

        <h3>Calculadora</h3>

        <p>
          Projeto para treino de lógica e JavaScript.
        </p>

      </a>

      <a href="#" class="project-card">

        <img src="https://picsum.photos/402/200" alt="Projeto">

        <h3>Login System</h3>

        <p>
          Tela de login moderna responsiva.
        </p>

      </a>

    </div>

  </section>

  <!-- CONTATO -->
  <section class="contact" id="contact">

    <h2>Contato</h2>

    <div class="contact-links">

      <a href="https://github.com/DevJotaD">
        <i class="fa-brands fa-github"></i>
        GitHub
      </a>

      <a href="https://www.linkedin.com/in/jardiel-ryan-70745b242/">
        <i class="fa-brands fa-linkedin"></i>
        LinkedIn
      </a>

      <a href="mailto:jardieldev@gmail.com">
        <i class="fa-solid fa-envelope"></i>
        Email
      </a>

    </div>

  </section>

  <!-- FOOTER -->
  <footer>
    <p>© 2026 - DevJotaD | Todos os direitos reservados</p>
  </footer>

</body>
</html>

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
  scroll-behavior: smooth;
}

body{
  background: #050816;
  color: white;
  overflow-x: hidden;
}

/* NAVBAR */

header{
  position: fixed;
  width: 100%;
  top: 0;
  z-index: 1000;
  background: rgba(5,8,22,0.8);
  backdrop-filter: blur(10px);
}

nav{
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px 10%;
}

nav h1{
  color: #4f8cff;
}

nav ul{
  display: flex;
  list-style: none;
  gap: 30px;
}

nav a{
  color: white;
  text-decoration: none;
  transition: 0.3s;
}

nav a:hover{
  color: #4f8cff;
}

/* HERO */

.hero{
  min-height: 100vh;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 120px 10%;
}

.hero-text{
  max-width: 600px;
}

.hero-text h2{
  font-size: 30px;
}

.hero-text h1{
  font-size: 60px;
  color: #4f8cff;
}

.hero-text h3{
  font-size: 30px;
  margin-bottom: 20px;
}

.hero-text p{
  color: #bdbdbd;
  line-height: 1.6;
  margin-bottom: 30px;
}

.hero-buttons{
  display: flex;
  gap: 20px;
}

.btn,
.btn-outline{
  padding: 12px 28px;
  border-radius: 8px;
  text-decoration: none;
  transition: 0.3s;
}

.btn{
  background: #4f8cff;
  color: white;
}

.btn:hover{
  transform: translateY(-3px);
}

.btn-outline{
  border: 1px solid #4f8cff;
  color: #4f8cff;
}

.btn-outline:hover{
  background: #4f8cff;
  color: white;
}

.hero-image img{
  width: 700px;
}

/* SEÇÕES */

section{
  padding: 100px 10%;
}

section h2{
  text-align: center;
  font-size: 40px;
  margin-bottom: 50px;
  color: #4f8cff;
}

/* SOBRE */

.about p{
  max-width: 700px;
  margin: auto;
  text-align: center;
  line-height: 1.8;
  color: #bdbdbd;
}

/* SKILLS */

.skills-container{
  display: flex;
  justify-content: center;
  gap: 30px;
  flex-wrap: wrap;
}

.skill-card{
  width: 180px;
  padding: 40px;
  background: #111827;
  border-radius: 15px;
  text-align: center;
  transition: 0.3s;
}

.skill-card:hover{
  transform: translateY(-10px);
}

.skill-card i{
  font-size: 50px;
  margin-bottom: 20px;
  color: #4f8cff;
}

/* PROJETOS */

.project-container{
  display: flex;
  gap: 30px;
  flex-wrap: wrap;
  justify-content: center;
}

.project-card{
  width: 350px;
  background: #111827;
  border-radius: 15px;
  overflow: hidden;
  text-decoration: none;
  color: white;
  transition: 0.3s;
}

.project-card:hover{
  transform: translateY(-10px);
}

.project-card img{
  width: 100%;
}

.project-card h3{
  padding: 20px 20px 10px;
}

.project-card p{
  padding: 0 20px 20px;
  color: #bdbdbd;
}

/* CONTATO */

.contact-links{
  display: flex;
  justify-content: center;
  gap: 30px;
  flex-wrap: wrap;
}

.contact-links a{
  padding: 15px 25px;
  background: #111827;
  border-radius: 10px;
  color: white;
  text-decoration: none;
  transition: 0.3s;
}

.contact-links a:hover{
  background: #4f8cff;
}

/* FOOTER */

footer{
  text-align: center;
  padding: 30px;
  color: #999;
}

/* FUNDO ANIMADO */

.background-animation{
  position: fixed;
  width: 100%;
  height: 100%;
  overflow: hidden;
  z-index: -1;
}

.background-animation span{
  position: absolute;
  width: 20px;
  height: 20px;
  background: rgba(79,140,255,0.15);
  border-radius: 50%;
  animation: animate 15s linear infinite;
  bottom: -150px;
}

.background-animation span:nth-child(1){
  left: 10%;
  width: 40px;
  height: 40px;
}

.background-animation span:nth-child(2){
  left: 30%;
  animation-duration: 12s;
}

.background-animation span:nth-child(3){
  left: 50%;
  width: 60px;
  height: 60px;
}

.background-animation span:nth-child(4){
  left: 70%;
  animation-duration: 18s;
}

.background-animation span:nth-child(5){
  left: 90%;
  width: 35px;
  height: 35px;
}

@keyframes animate{
  0%{
    transform: translateY(0) rotate(0deg);
    opacity: 0;
  }

  10%{
    opacity: 1;
  }

  100%{
    transform: translateY(-1000px) rotate(720deg);
    opacity: 0;
  }
}

/* RESPONSIVO */

@media(max-width: 900px){

  nav{
    flex-direction: column;
    gap: 20px;
  }

  .hero{
    flex-direction: column;
    text-align: center;
    gap: 50px;
  }

  .hero-buttons{
    justify-content: center;
  }

  .hero-text h1{
    font-size: 45px;
  }

  .hero-image img{
    width: 250px;
  }
}
