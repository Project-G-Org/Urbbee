<script>
  import logo from "$lib/images/URBBEE_LOGO.png"
	import Icons from "./icons.svelte";
</script>

<footer>
  <div id="left">
    <div class="logo-container">
      <img src={logo} alt="logo" width="102">
      <h1>URB<span class="color-main">BEE</span></h1>
    </div>

    <div id="social-media">
      <h4>NOS SIGA EM NOSSAS REDES SOCIAIS</h4>

      <div id="icons">
        <Icons />
      </div>
    </div>
  </div>

  <div id="right">
    <div>
      <h4 class="color-main">TECNOLOGIAS</h4>

      <a href='#tec'>BUILDER BUDDY</a>
      <a href='#tec'>POKEGELO-CLI</a>
      <a href='#tec'>PANGOLINY</a>
      <a href='#tec'>UNIVERSITY-API</a>
    </div>

    <div>
      <h4 class="color-main">SOBRE NÓS</h4>

      <a href='#about-us'>QUEM SOMOS</a>
    </div>

    <div>
      <h4 class="color-main">ENTRE EM CONTATO</h4>

      <span>(31) 98865-4602</span>
      <span>(31) 97300-8566</span>
      <a href='mailto:'>URBEE@gmail.com</a>
      <span>SEJA UMA ABELHA</span>
    </div>
  </div>
</footer>

<style lang="scss">
  footer {
    display: flex;
    width: 100vw;
    padding: 64px 128px;
    justify-content: space-between;
    align-items: flex-start;

    color: var(--bg);
    background-color: var(--dark);

    #right {
      display: flex;
      flex: row;
      gap: 10vw;
      width: 60%;

      div {
        display: flex;
        flex-direction: column;
        padding: 0;
        
        h4 {
          font-size: 36px;
        }

        span, a {
          font-style: normal;
          color: var(--bg);
          text-decoration: none;
          font-size: 24px;
        }
      }
    }

    #left {
      width: 40%;
      display: flex;
      flex-direction: column;
      gap: 2vh;

      h4 {
        font-size: 32px;
      }
    }
  }

  div.logo-container {
    color: var(--bg);
    margin-left: 0;
  }
</style>