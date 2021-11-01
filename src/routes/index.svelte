<style>
  img {
    height: 10em;
    width: 10em;
    border-radius: 100%;
    margin: auto;
  }

  div {
    flex-basis: 60%;
    margin-right: 3em;
  }

  section {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    margin-bottom: 3em;
  }

  section:nth-child(2) {
    background-color: #dec8de;
    padding: 1em;
  }

  aside {
    background-color: #6b2e6d;
    border-radius: 0.5em;
    padding: 1em;
    color: white;
    max-width: 15em;
    text-align: center;
  }

  @media screen and (max-width: 800px) {
    section {
      flex-direction: column;
      align-items: center;
      width: 84%;
      margin: auto;
    }

    aside {
      margin-top: 1em;
      margin-bottom: 1em;
    }
  }
</style>

<section>
  <div>
    <h1>Hej, det är jag som är Krille! 👋</h1>
    <p>
      Jag är en fullstack-utvecklare på
      <a
        target="_blank"
        rel="noopener noreferrer"
        href="https://www.isotop.se/">
        Isotop
      </a>
      där jag får utveckla både webb och mobilapplikationer åt våra kunder och i
      interna projekt.
    </p>
    <p>
      Jag har ett brett intresse av systemutveckling och arbetar gärna med ett
      holistiskt perspektiv på utveckling av produkter och tjänster.
    </p>
    <p>
      Utöver teknik är jag också intresserad av agil metodik. I SCRUM-projekt
      jobbar jag ibland som Scrum Master och produktägare.
    </p>
  </div>
  <aside>
    <img src="/krille.png" alt="krille" />
    <p>
      Jag finns på
      <a
        target="_blank"
        rel="noopener noreferrer"
        href="https://www.linkedin.com/in/kristoffer-karlsson-a1878311b/">
        LinkedIn!
      </a>
      Passa på att ta en titt på
      <a
        href="https://www.linkedin.com/company/isotop-ab/"
        target="_blank"
        rel="noopener noreferrer">
        Isotops hemsida
      </a>
      också för att få en bild av vad vi jobbar med.
    </p>
  </aside>
</section>
