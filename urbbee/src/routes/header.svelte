<header>
  <nav>
    <div id="logo-container">
      <img src="#" alt="logo">URB<span>BEE</span>
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
      --gap: 15%;

      height: 100%;
      width: 100%;

      display: flex;
      flex-direction: row;
      gap: var(--gap);
      
      justify-content: space-between;
      align-items: center;

      color: var(--bg);

      #logo-container {
        width: 25%;
        margin-left: 2vw;
      }

      #links-container {
        width: calc(80% - var(--gap));

        ul {
          width: inherit;

          display: inline-flex;
          justify-content: space-between;
          gap: 10%;
        }

        a {
          text-decoration: none;
          color: var(--bg);
        }
      }
    }
  }
</style>