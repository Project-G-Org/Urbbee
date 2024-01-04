<script>
  import logo from "$lib/images/URBBEE_LOGO.png"
</script>

<header>
  <nav>
    <div id="logo-container">
      <img src={logo} alt="logo" width="102">
      <h1>URB<span class="color-bg">BEE</span></h1>
    </div>

    <div id="links-container">
      <ul>
        <li><a href="#">QUEM SOMOS?</a></li>
        <li><a href="#">NOSSAS TECNOLOGIAS?</a></li>
        <li><a href="#">SAIBA MAIS?</a></li>
      </ul>
    </div>
  </nav>
</header>

<style lang="scss">
  header {
    background-color: var(--main);

    height: 13.2vh;
    max-height: 13.2vh;
    padding: 5px;
 
    nav {
      --gap: 14%;

      height: 100%;
      width: 100%;

      display: flex;
      flex-direction: row;
      gap: var(--gap);
      
      justify-content: space-between;
      align-items: center;

      color: var(--bg);

      #logo-container {
        width: 60%;
        
        display: inline-flex;
        align-items: center;
        margin-left: 7vw;

        color: var(--dark);

        h1 {
          font-size: 4rem;
        }
      }

      #links-container {
        width: calc(100% - var(--gap));
        margin-left: 14vw;

        ul {
          width: inherit;

          display: inline-flex;
          justify-content: space-between;
          gap: 10%;

          list-style: none;
        }

        a {
          text-decoration: none;
          color: var(--bg);
          font-weight: 600;
          font-size: 2rem;
        }
      }
    }
  }
</style>