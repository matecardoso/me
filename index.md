---
layout: home
---

<div class="language-buttons">
  <img src="{{ '/assets/images/Flag_of_Brazil.svg' | relative_url }}" alt="Português" onclick="showPortuguese()">
  <img src="{{ '/assets/images/Flag_of_the_United_States.svg' | relative_url }}" alt="English" onclick="showEnglish()">
</div>

<div id="portuguese" class="language-content">

  <section class="section is-white has-text-centered">
    <div class="container">
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

  <section class="section is-primary has-text-centered">
    <div class="container">
      {% include profile.html 
        name="Mateus Cardoso" 
        function="Desenvolvedor Fullstack Sênior" 
        stack="PHP | Laravel | Vue | React | React-native" 
        content='
          <p>Profissional Fullstack apaixonado pela arte da programação, trago uma bagagem de quase 20 anos de envolvimento com a programação, começando como hobby e, nos últimos 10 anos, dedicando-me exclusivamente a trabalhar nesse universo fascinante.</p>
          <p>Durante esse tempo, concentrei meu foco no desenvolvimento com PHP puro e Laravel, além de sólidos conhecimentos em React, React-Native, Vue.js e jQuery. Minha expertise se destaca especialmente em Laravel e Vue.js, mas abrange também uma ampla gama de tecnologias.</p>
          <p>Ao longo dessa jornada intensa, atuei desde o planejamento, construção e sustentação de aplicações modernas, até a refatoração de sistemas legados, consolidando meu conhecimento em padrões, arquitetura, qualidade e boas práticas. Minha trajetória inclui tanto a entrega de soluções inovadoras em prazos desafiadores quanto a busca pela melhor implementação e qualidade possível.</p>
          <p>Além da experiência profissional, trago uma vasta formação acadêmica, onde além da formação técnica em informática, graduação em Análise e Desenvolvimento de Sistemas e pós-graduação em Data Science, também cursei Ciência da Computação pelo Instituto Federal Catarinense até a penúltima fase do curso. Pausei meus estudos para aproveitar uma oportunidade profissional significativa que me levou a mudar de cidade. Assim, trago comigo o domínio de vários conceitos computacionais além do desenvolvimento de software em si, abrangendo, entre outros, aspectos de segurança, redes e infraestrutura.</p>
          <p>Enfrentei desafios emocionantes, explorando diversas linguagens e tecnologias com uma abordagem proativa e orientada a resultados. Minha capacidade de trabalhar colaborativamente em equipe me permite contribuir de maneira significativa para o sucesso dos projetos.</p>
          <p>👨‍💻 Profissional Fullstack com 10 anos de experiência<br> 🌟 Especialista em PHP, Laravel e Vue.js<br> 🚀 Apaixonado por superar expectativas e agregar valor aos projetos</p>
        ' 
      %}
    </div>
  </section>
</div>

<div id="english" class="language-content" style="display:none;">
  <section class="section is-white has-text-centered">
    <div class="container">
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

  <section class="section is-primary has-text-centered">
    <div class="container">
      {% include profile.html 
        name="Mateus Cardoso" 
        function="Senior Fullstack Developer" 
        stack="PHP | Laravel | Vue | React | React-native" 
        content='
          <p>Fullstack professional passionate about the art of programming, with nearly 20 years of involvement in the field, starting as a hobby and exclusively working in this fascinating universe for the past 10 years.</p>
          <p>During this time, I focused on development with pure PHP and Laravel, along with solid knowledge in React, React-Native, Vue.js, and jQuery. My expertise particularly stands out in Laravel and Vue.js, but it also spans a wide range of technologies.</p>
          <p>Throughout this intense journey, I have worked on planning, building, and maintaining modern applications, as well as refactoring legacy systems, consolidating my knowledge in patterns, architecture, quality, and best practices. My experience includes delivering innovative solutions under challenging deadlines and striving for the best implementation and quality possible.</p>
          <p>In addition to my professional experience, I have extensive academic training, including technical education in IT, a degree in Systems Analysis and Development, and a postgraduate degree in Data Science. I also studied Computer Science until the second-to-last semester, pausing my studies to seize a significant professional opportunity that required me to move to a different city. This academic background gives me mastery of various computational concepts beyond software development, encompassing aspects of security, networks, and infrastructure.</p>
          <p>I have faced exciting challenges, exploring various languages and technologies with a proactive and results-oriented approach. My ability to work collaboratively in a team allows me to contribute significantly to the success of projects.</p>
          <p>👨‍💻 Fullstack professional with 10 years of experience<br> 🌟 Specialist in PHP, Laravel, and Vue.js<br> 🚀 Passionate about exceeding expectations and adding value to projects</p>
        ' 
      %}
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
