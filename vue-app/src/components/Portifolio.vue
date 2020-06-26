<template>
  <div class="Portifolio">
    <header>
      <section class="hero is-fullheight top-screen">
        <div class="hero-body">
          <div class="container has-text-centered">
            <h1 class="welcome-text">Welcome</h1>
            <p class="welcome-text animated-text animate__animated animate__bounceInDown">.</p>
          </div>
        </div>
      </section>
    </header>
    <article class="has-text-centered">
      <div class="columns is-inline-block-mobile is-centered">
        <div class="column">
          <div class="container">
            <header>
              <div class="hello-container">
                <img
                  id="circle-image"
                  class="icon-image"
                  src="../images/Circle-image.svg"
                  alt="Figma icon"
                />
                <h2 class="title hello-title">Hi. I’m Lara</h2>
              </div>
            </header>
            <h3
              class="subtitle"
            >I’m a System Development student currently living in Joinville, Brazil. I have a passion for front-end development, UI and UX.</h3>
          </div>
          <div class="container">
            <h2 class="title">Projects</h2>
            <h3 class="subtitle click-link">
              <a href="https://cricketgate.web.app/login" target="_blank"><span>CricketGate</span></a>
            </h3>
            <h3 class="subtitle click-link">
              <a
                href="https://medium.com/@larabeatrizdeoliveira/estudo-de-caso-ui-ux-trazer-uma-nova-experi%C3%AAncia-para-os-usu%C3%A1rios-da-the-body-shop-por-meio-do-b9d379e47650"
                target="_blank"
              ><span>Study case</span></a>
            </h3>
          </div>
          <div class="container">
            <h2 class="title" id="tecnologies-text">Tecnologies</h2>
            <img class="icon-image" src="../images/JS-icon.svg" alt="Javascript icon" />
            <img class="icon-image" src="../images/Vue-icon.svg" alt="Vue icon" />
            <img class="icon-image" src="../images/CSS-icon.svg" alt="CSS icon" />
            <img class="icon-image" src="../images/HTML-icon.svg" alt="HTML icon" />
            <img class="icon-image" src="../images/Figma-icon.svg" alt="Figma icon" />
          </div>
          <div class="container">
            <h2 class="title" id="social-medias">Let’s be internet BFFs</h2>
            <a href="https://github.com/lrbtz" target="_blank">
              <img
                class="icon-image"
                src="../images/Github-icon.svg"
                alt="lcon to access my github page"
              />
            </a>
            <a href="https://www.linkedin.com/in/lara-beatriz-de-oliveira/" target="_blank">
              <img
                class="icon-image"
                src="../images/Linkedin-icon.svg"
                alt="lcon to access my linkedin page"
              />
            </a>
            <a href="https://medium.com/@larabeatrizdeoliveira" target="_blank">
              <img
                class="icon-image"
                src="../images/Medium-icon.svg"
                alt="lcon to access my medium page"
              />
            </a>
            <a href="mailto:lara.bia@outlook.com.br" target="_blank">
              <img class="icon-image" src="../images/Email-icon.svg" alt="lcon to send me an email" />
            </a>
          </div>
        </div>
      </div>
    </article>
    <footer class="footer has-text-centered">Lara Oliveira. All Rights Reserved.</footer>
  </div>
</template>

<script>
export default {
  name: "Portifolio"
};
</script>