<script>
  import bannerOne from '$lib/images/BANNER1.png';
</script>

<main>
  <section id="intro-banner">
    <img src={bannerOne} width="40%" alt="banner">

    <article>
      <h1>A URB<span class="color-main">BEE</span> É A SUA MANEIRA DE SOLUCIONAR OS <span class="color-main">SEUS</span> <span class="color-main">PROBLEMAS</span> USANDO O MELHOR DA <span class="color-main">TECNOLOGIA.</span></h1>
    </article>
  </section>

  <section>
    <h1>NOSSAS TECNOLOGIAS</h1>

    <div id="tec-row">
      <img src="" alt="builder buddy logo">
      <img src="" alt="pokegelo cli logo">
      <img src="" alt="university api logo">
      <img src="" alt="pangoliny logo">
    </div>
  </section>

  <section id="builder-buddy-banner">
    <img src="#" alt="builder buddy logo">

    <article>
      <h1>BUILDER BUDDY</h1>
      <p>a rede social voltada para a divulgação da arquitetura, engenharia e arte urbana.</p>
    </article>
  </section>

  <section id="div-banner">
    <img src="" alt="div banner">
  </section>

  <section>
    <h1>QUEM SOMOS?</h1>
    <article>A URB<span class="text-main">BEE</span> É UMA ORGANIZAÇÃO DE SOLUÇÕES DIGITAIS E GERENCIADORA DA REDE SOCIAL BUILDERBUDDY</article>

    <div id="team-pics-row">
      <div class="team-pic">
        <img src="" alt="team picture">
        <h2 class="trailing">GABRIEL SPINOLA</h2>
      </div>

      <div class="team-pic">
        <img src="" alt="team picture">
        <h2 class="trailing">LUCAS VINICIUS</h2>
      </div>

      <div class="team-pic">
        <img src="" alt="team picture">
        <h2 class="trailing">VICTOR LUIZ</h2>
      </div>
    </div>

    <section>
      <h1>ENTRE EM CONTATO</h1>

      <form>
        <label for="name">NOME</label>
        <input type="text" id="name" name="name" required>

        <label for="email">EMAIL</label>
        <input type="email" id="email" name="email" required>

        <label for="message">MESSAGEM</label>
        <textarea id="message" name="message"></textarea>

        <input type="submit" value="ENVIAR">
      </form>
    </section>
  </section>
</main>

<style lang="scss">
  section {
    margin: 6.6vh 0;
  }

  section#intro-banner {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    gap: 64px;

    margin-top: 0;

    width: 100vw;
    height: 75.5vh;
    max-height: 75.5vh;

    color: var(--bg);
    background-color: var(--dark);

    article {
      height: 100%;
      width: 60%;
      display: flex;

      align-items: center;

      font-size: 7.93rem;
      line-height: 76px;
    }
  }
</style>
