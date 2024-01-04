<script>
  import logo from "$lib/images/URBBEE_LOGO.png"
</script>

<footer>
  <div class="logo-container">
    <img src={logo} alt="logo" width="102">
    <h1>URB<span class="color-bg">BEE</span></h1>
  </div>

  <div id="right">
    <div>
      <h4>TECNOLOGIAS</h4>

      <span>BUILDER BUDDY</span>
      <span>POKEGELO-CLI</span>
      <span>PANGOLINY</span>
      <span>UNIVERSITY-API</span>
    </div>

    <div>
      <h4>SOBRE NÓS</h4>

      <span>QUEM SOMOS</span>
    </div>

    <div>
      <h4>ENTRE EM CONTATO</h4>

      <span>(31) 98865-4602</span>
      <span>(31) 97300-8566</span>
      <span>URBEE@gmail.com</span>
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
  }
</style>