---
layout: home
---

<div class="language-buttons">
  <button class="button is-light" onclick="showPortuguese()">
    <img src="{{ '/assets/images/Flag_of_Brazil.svg' | relative_url }}" alt="Português">
  </button>
  <button class="button is-light" onclick="showEnglish()">
    <img src="{{ '/assets/images/Flag_of_the_United_States.svg' | relative_url }}" alt="English">
  </button>
</div>

<div id="portuguese" class="language-content">
  <section class="hero is-white has-text-centered">
    <div class="hero-body">
      <div class="container">
        <div class="columns is-centered">
          <div class="column">
            <h1 class="title is-spaced is-size-1-desktop is-size-2-tablet is-size-3-mobile">Desenvolvedor Fullstack Sênior</h1>
            <h2 class="subtitle is-size-4-tablet">Eu projeto e codifico coisas simples e bonitas, e amo o que faço.</h2>
            <img class="avatar" src="https://via.placeholder.com/150" alt="Avatar">
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section is-medium is-primary has-text-centered">
    <div class="container">
      <div class="columns is-centered">
        <div class="column is-three-fifths">
          <h1 class="title is-spaced is-size-3-desktop is-size-4-mobile">Olá, eu sou Mateus. Prazer em conhecê-lo.</h1>
          <h2 class="subtitle is-size-5-desktop has-text-weight-normal">Desde o início da minha jornada como desenvolvedor há X anos, fiz trabalhos remotos para agências, consultei startups e colaborei com pessoas talentosas para criar produtos digitais para uso comercial e de consumidores. Estou sempre confiante, naturalmente curioso e perpetuamente trabalhando para melhorar minhas habilidades.</h2>
        </div>
      </div>
    </div>
  </section>

  <section class="section is-medium is-white has-text-centered">
    <div class="container">
      <h1 class="title is-size-3-desktop is-size-4-mobile">Redirecionamentos</h1>
      <div class="buttons is-centered">
        <a href="https://github.com/Mate38" class="button is-primary" target="_blank">
          <span class="icon"><i class="fab fa-github"></i></span>
          <span>Meu Github Antigo</span>
        </a>
        <a href="https://github.com/matecardoso" class="button is-secondary" target="_blank">
          <span class="icon"><i class="fab fa-github"></i></span>
          <span>Meu Github Novo</span>
        </a>
        <a href="https://www.linkedin.com/in/matecardoso/" class="button is-info" target="_blank">
          <span class="icon"><i class="fab fa-linkedin"></i></span>
          <span>Meu LinkedIn</span>
        </a>
        <a href="https://drive.google.com/drive/folders/14OL-ox9tiJ7q3jynN2_aswSQuf4FTPOT?usp=sharing" class="button is-success" target="_blank">
          <span class="icon"><i class="fas fa-file-alt"></i></span>
          <span>Link para Currículos</span>
        </a>
      </div>
    </div>
  </section>
</div>

<div id="english" class="language-content" style="display:none;">
  <section class="hero is-white has-text-centered">
    <div class="hero-body">
      <div class="container">
        <div class="columns is-centered">
          <div class="column">
            <h1 class="title is-spaced is-size-1-desktop is-size-2-tablet is-size-3-mobile">Senior Fullstack Developer</h1>
            <h2 class="subtitle is-size-4-tablet">I design and code beautifully simple things, and I love what I do.</h2>
            <img class="avatar" src="https://via.placeholder.com/150" alt="Avatar">
          </div>
        </div>
      </div>
    </div>
  </section>

  <section class="section is-medium is-primary has-text-centered">
    <div class="container">
      <div class="columns is-centered">
        <div class="column is-three-fifths">
          <h1 class="title is-spaced is-size-3-desktop is-size-4-mobile">Hi, I’m Mateus. Nice to meet you.</h1>
          <h2 class="subtitle is-size-5-desktop has-text-weight-normal">Since beginning my journey as a developer X years ago, I have done remote work for agencies, consulted for startups, and collaborated with talented people to create digital products for commercial and consumer use. I'm quietly confident, naturally curious, and perpetually working on improving my skills.</h2>
        </div>
      </div>
    </div>
  </section>

  <section class="section is-medium is-white has-text-centered">
    <div class="container">
      <h1 class="title is-size-3-desktop is-size-4-mobile">Redirects</h1>
      <div class="buttons is-centered">
        <a href="https://github.com/Mate38" class="button is-primary" target="_blank">
          <span class="icon"><i class="fab fa-github"></i></span>
          <span>My Old Github</span>
        </a>
        <a href="https://github.com/matecardoso" class="button is-secondary" target="_blank">
          <span class="icon"><i class="fab fa-github"></i></span>
          <span>My New Github</span>
        </a>
        <a href="https://www.linkedin.com/in/matecardoso/" class="button is-info" target="_blank">
          <span class="icon"><i class="fab fa-linkedin"></i></span>
          <span>My LinkedIn</span>
        </a>
        <a href="https://drive.google.com/drive/folders/14OL-ox9tiJ7q3jynN2_aswSQuf4FTPOT?usp=sharing" class="button is-success" target="_blank">
          <span class="icon"><i class="fas fa-file-alt"></i></span>
          <span>Link to Resumes</span>
        </a>
      </div>
    </div>
  </section>
</div>

<script>
  function showPortuguese() {
    document.getElementById('portuguese').style.display = 'block';
    document.getElementById('english').style.display = 'none';
  }

  function showEnglish() {
    document.getElementById('portuguese').style.display = 'none';
    document.getElementById('english').style.display = 'block';
  }
</script>
