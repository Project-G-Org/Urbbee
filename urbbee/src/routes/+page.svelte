<script>
  import bannerOne from '$lib/images/BANNER1.png';
  import builderBuddyLogo from '$lib/images/builder_buddy.png'
  import uniApiLogo from '$lib/images/uni_api_logo.png'
  import pokegeloCliLogo from '$lib/images/pokegelo_cli_logo.png'
  import pangolinyLogo from '$lib/images/pangoliny_logo.png'
  import handBanner from '$lib/images/hand_banner.png'
  import autistaPic from '$lib/images/LUCAS_NATALINO.jpg'
  import lindaoPic from '$lib/images/VICTOR_LUIZ_NATALINO.jpg'
</script>

<main>
  <section id="intro-banner">
    <img src={bannerOne} width="40%" alt="banner">

    <article>
      <h1>A URB<span class="color-main">BEE</span> É A SUA MANEIRA DE SOLUCIONAR OS <span class="color-main">SEUS</span> <span class="color-main">PROBLEMAS</span> USANDO O MELHOR DA <span class="color-main">TECNOLOGIA.</span></h1>
    </article>
  </section>

  <section id="tec">
    <h2>NOSSAS TECNOLOGIAS</h2>

    <article id="tec-list">
      <div>
        <img id="builder-buddy" src={builderBuddyLogo} width="128" alt="builder buddy logo">
      </div>

      <div>
        <img src={pokegeloCliLogo} width="128" alt="pokegelo cli logo">
      </div>

      <div>
        <img src={uniApiLogo} width="128" alt="university api logo">
      </div>

      <div>
        <img src={pangolinyLogo} width="128" alt="pangoliny logo">
      </div>
    </article>
  </section>

  <section id="builder-buddy-banner">
    <img src={builderBuddyLogo} width="512" alt="builder buddy logo">

    <article>
      <h1><span class="color-bb-light">BUILDER</span><br><span class="color-bb-dark">BUDDY</span></h1>
      <p>a rede social voltada para a divulgação da <span class="color-bb-light">arquitetura</span>, <span class="color-bb-dark">engenharia</span> e <span class="color-bb-light">arte urbana.</span></p>
    </article>
  </section>

  <section id="div-banner">
    <img src={handBanner} alt="div banner">
  </section>

  <section id="about-us">
    <h2>QUEM SOMOS?</h2>
    <article>
      <h3>A URB<span class="color-main">BEE</span> É UMA ORGANIZAÇÃO DE SOLUÇÕES DIGITAIS E GERENCIADORA DA REDE <span class="color-bb-light">SOCIAL</span> <span class="color-bb-dark">BUILDERBUDDY</span></h3>

      <div id="team-pics-row">
        <div class="team-pic">
          <img src={lindaoPic} alt="team member">
          <h3 class="trailing">GABRIEL SPINOLA</h3>
        </div>

        <div class="team-pic">
          <img src={autistaPic} alt="team member">
          <h3 class="trailing">LUCAS VINICIUS</h3>
        </div>

        <div class="team-pic">
          <img src={lindaoPic} alt="team member">
          <h3 class="trailing">VICTOR<br>LUIZ</h3>
        </div>
      </div>
    </article>

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
  @import '../styles/landing-page.scss'
</style>
