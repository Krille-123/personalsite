<style>
  p {
    margin-top: 4px;
  }

  h2 {
    border-bottom: 1px solid #6b2e6d;
    display: inline-block;
    margin: 0;
  }

  section {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
  }

  article {
    border: 1px solid rgba(107, 46, 109, 0.3);
    padding: 2em;
    max-width: 39%;
    margin-bottom: 2rem;
    margin-right: 2em;
    box-shadow: 2px 2px 2px rgba(107, 46, 109, 0.3);
  }

  h1 {
    font-size: 1.3em;
    margin-bottom: 1.3em;
  }

  @media screen and (max-width: 894px) {
    article {
      margin: 0 auto 2rem auto;
      max-width: 80%;
    }

    h1 {
      margin: 0 auto 2rem auto;
      max-width: 95%;
    }
  }
</style>

<section>
  <h1>
    Detta är en snabb sammanfattning av de tekniker som jag har jobbat med
    professionellt. Fråga mig gärna om någon av dem så kan vi ha en djupare
    diskussion!
  </h1>
  <article>
    <h2>Android</h2>
    <p>
      Mitt första erfarenhet av apputveckling var Androidutveckling med Kotlin.
      Jag byggde Androidversionen av en app som skannade NFC-chip i passerkort
      och validerade certifikaten som var lagrade på dem.
    </p>
    <p>
      Det var intressant att se hur mycket plattformen utvecklats och
      förbättrats, och kul att få integrera med hårdvara.
    </p>
  </article>

  <article>
    <h2>Flutter</h2>
    <p>
      Det senaste verktyget i min toolbox är Googles Flutter. Jag trivs mycket
      bra med Dart och Flutters toolkit för att bygga UI. Just nu jobbar jag i
      ett appprojekt som integrerar med bluetoothprodukter.
    </p>
    <p>
      Ett aspekt av Flutter jag utforskar är möjligheten att bygga
      plattformsagnostiska applikatoner och publicera till iOS/Android, desktop
      och webb. Flutter for web blir bättre och bättre och Flutter börjar också
      utmana inom desktoputveckling.
    </p>
  </article>
  <article>
    <h2>.NET</h2>
    <p>
      Jag har ett par års erfarenhet av fullstack-utveckling där backend har
      byggts på .NET-plattformen med C#. Episerver och Umbraco har använts som
      CMS.
    </p>
    <p>
      .NET-utvecklingen har gjorts med cloudplattformen Azure, där jag bland
      annat har jobbat mycket med CI/CD i Azure devops, och varit med i en
      migrering från on premise-hosting till Azure. Som databas har jag använt
      dokumentdatabasen RavenDB.
    </p>
  </article>
  <article>
    <h2>Frontend</h2>
    <p>
      Sedan 5 år tillbaka har React varit mitt mest använda verktyg till att
      bygga moderna webbklienter. Jag har byggt både med ramverket Next.js, och
      hemsnickrade lösningar med Redux som state manager.
    </p>
    <p>
      Ett annat ramverk ovanpå React som jag har använt i våra projekt är
      Gatsby.js. Gatsby är en static site generator som är väldigt härligt att
      jobba med när man vill hämta content från källor som t.ex. headless CMS
      och slippa riskerna och komplexiteten med att servera klienten från en
      server. I projekt där det är viktigt med sitens tillgänglighet och
      responstid trots stora användarmängder under kort tid, har vi använt det i
      kombination med Contentful som CMS och Cloudflare som hosting.
    </p>
    <p>
      Ett ramverk som jag tycker om och har labbat en del privat med, men tyvärr
      inte använt i skarpt projekt än, är Svelte.js. Denna site är byggd med
      Svelte!
    </p>
  </article>
  <article>
    <h2>Firebase</h2>
    <p>
      Firebase (byggt ovanpå Google Cloud Platform) har varit en stor hjälp vid
      apputveckling, speciellt när vi snabbt har behövt få igång fungerande
      appar för att sälja in projekt eller skapa appar för hifi-prototyper.
    </p>
    <p>
      Firestore är Firebase dokumentdatabas som stödjer realtidsuppdateringar
      out of the box. Med bra SDK till webb, Android och Dart har det varit
      ovärdeligt för att snabbt slänga ihop en häftig demo med real time updates
      i applikationerna. Firebase har också använts till statistiktracking av
      interaktioner, kraschrapportering och distribuering av testversioner av
      apparna.
    </p>
  </article>
</section>
