<script>
  import bannerOne from '$lib/images/BANNER1.png';
  import builderBuddyLogo from '$lib/images/builder_buddy.png'
  import uniApiLogo from '$lib/images/uni_api_logo.png'
  import pokegeloCliLogo from '$lib/images/pokegelo_cli_logo.png'
  import pangolinyLogo from '$lib/images/pangoliny_logo.png'
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
        <img src={builderBuddyLogo} width="128" alt="builder buddy logo">
      </div>

      <div>
        <img src={pokegeloCliLogo} width="128" alt="pokegelo cli logo">
      </div>

      <div>
        <img src={uniApiLogo} width="128" alt="university api logo">
      </div>

      <div>
        <img id="pangoliny" src={pangolinyLogo} width="128" alt="pangoliny logo">
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

  section#tec {
    display: flex;
    flex-direction: column;

    text-align: center;
    justify-content: center;
    padding: 128px;

    h2 {
      font-size: 4rem;  
    }

    article#tec-list {
      display: flex;
      flex-direction: row;

      margin: 0 auto;
      gap: 4vw;

      div {
        width: 10vw;
        height: 21vh;
      }

      img {
        margin-top: 15px;
        width: 132px;
        height: 132px;
        border-radius: 32px;
        box-shadow: 0 0 17px 2px rgba(0, 0, 0, 0.10);
      }
    }
  }

  section#builder-buddy-banner {
    height: 80vh;
    width: 80.2vw;

    margin: 0 auto;
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 4vw;
    overflow: visible;

    img {
      width: 512px;
      height: 512px;
      border-radius: 32px;
      box-shadow: 0 0 17px 2px rgba(0, 0, 0, 0.10);
    }

    article {
      width: 50%;

      h1 {
        font-size: 12rem;
        line-height: 115px;
        overflow: visible;
        font-weight: 400;
      }

      p {
        font-size: 3.8rem;
        line-height: 35px;
        overflow: visible;
        font-weight: 400;
      }
    }
  }
</style>
