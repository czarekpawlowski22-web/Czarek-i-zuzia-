<!doctype html>
<html lang="pl">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#0d0b0c">
  <meta name="description" content="Prywatne wspomnienia Zuzi i Czarka.">
  <title>Zuzia & Czarek — nasza historia</title>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

  <link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@500;600;700&family=DM+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="style.css">
</head>

<body>

  <div class="grain"></div>

  <header class="nav">
    <a class="brand" href="#top">Z<span>&</span>C</a>

    <nav>
      <a href="#historia">Historia</a>
      <a href="#wspomnienia">Wspomnienia</a>
      <a href="#list">Dla Ciebie</a>
    </nav>

    <button class="music-btn" id="musicBtn" aria-label="Włącz muzykę">
      ♪
    </button>
  </header>

  <main id="top">

    <!-- HERO -->

    <section class="hero">

      <div class="hero-copy reveal">

        <p class="eyebrow">
          01.12.2023 · i tak już zostało
        </p>

        <h1>
          Zuzia <i>&</i><br>
          Czarek
        </h1>

        <p class="hero-sub">
          Małe chwile. Wielkie wspomnienia.<br>
          Nasza własna mała historia.
        </p>

        <a class="scroll" href="#historia">
          <span>↓</span>
          poznaj naszą historię
        </a>

      </div>

      <div class="hero-photo reveal">

        <img
          src="assets/04-budapeszt.jpeg"
          alt="Zuzia i Czarek nocą"
        >

        <div class="photo-note">
          jeden z tych momentów,<br>
          które chce się zatrzymać
        </div>

      </div>

      <div class="hero-heart">
        ♥
      </div>

    </section>


    <!-- LICZNIK -->

    <section class="counter-section" id="historia">

      <div class="section-head reveal">

        <p class="eyebrow">
          01 / NASZA HISTORIA
        </p>

        <h2>
          Od tego dnia minęło...
        </h2>

      </div>

      <div class="counter reveal" id="counter">

        <div>
          <strong id="days">0</strong>
          <span>dni</span>
        </div>

        <div>
          <strong id="hours">0</strong>
          <span>godzin</span>
        </div>

        <div>
          <strong id="minutes">0</strong>
          <span>minut</span>
        </div>

        <div>
          <strong id="seconds">0</strong>
          <span>sekund</span>
        </div>

      </div>

      <p class="tiny-note">
        01 grudnia 2023 — dzień, od którego liczymy nasze „my”.
      </p>

    </section>


    <!-- HISTORIA -->

    <section class="story">

      <div class="story-image reveal">

        <img
          src="assets/01-stadion.jpeg"
          alt="Zuzia i Czarek na stadionie"
        >

      </div>

      <div class="story-copy reveal">

        <p class="eyebrow">
          02 / CHWILE
        </p>

        <h2>
          Nie potrzebujemy<br>
          wielkich rzeczy.
        </h2>

        <p>
          Najlepsze wspomnienia często zaczynają się od zwykłego
          „chodź, zrobimy zdjęcie”. A potem zostają z nami na długo.
        </p>

        <div class="quote">
          „Najfajniejsze jest to, że jeszcze tyle historii przed nami.”
        </div>

      </div>

    </section>


    <!-- GALERIA -->

    <section class="gallery-section" id="wspomnienia">

      <div class="section-head reveal">

        <p class="eyebrow">
          03 / WSPOMNIENIA
        </p>

        <h2>
          Nasze małe archiwum.
        </h2>

        <p>
          Zdjęcia, które nie potrzebują dodatkowego powodu,
          żeby wywołać uśmiech.
        </p>

      </div>


      <div class="gallery">

        <figure class="card tall reveal">

          <img
            src="assets/03-pies.jpeg"
            alt="Zuzia, Czarek i pies"
          >

          <figcaption>
            <span>01</span>
            razem, nawet z futrzastym pasażerem
          </figcaption>

        </figure>


        <figure class="card reveal">

          <img
            src="assets/02-smieszne-selfie.jpeg"
            alt="Śmieszne wspólne selfie"
          >

          <figcaption>
            <span>02</span>
            nasze normalne zachowanie
          </figcaption>

        </figure>


        <figure class="card wide reveal">

          <img
            src="assets/05-muszelki.jpeg"
            alt="Zuzia i Czarek na wyjeździe"
          >

          <figcaption>
            <span>03</span>
            każde miejsce jest lepsze we dwoje
          </figcaption>

        </figure>


        <figure class="card reveal">

          <img
            src="assets/06-akwarium.jpeg"
            alt="Zuzia w akwarium"
          >

          <figcaption>
            <span>04</span>
            małe odkrycia
          </figcaption>

        </figure>


        <figure class="card tall reveal">

          <img
            src="assets/07-lustro.jpeg"
            alt="Zuzia i Czarek przed lustrem"
          >

          <figcaption>
            <span>05</span>
            bez filtra, za to z nami
          </figcaption>

        </figure>

      </div>

    </section>


    <!-- FILMY -->

    <section class="video-section reveal">

      <div class="video-copy">

        <p class="eyebrow">
          04 / RUCHOME WSPOMNIENIA
        </p>

        <h2>
          Bo niektórych chwil<br>
          nie da się zatrzymać.
        </h2>

        <p>
          Więc zachowujemy je tutaj.
        </p>

      </div>


      <div class="videos">

        <video controls playsinline preload="metadata">

          <source
            src="assets/08-wspomnienie.mp4"
            type="video/mp4"
          >

        </video>


        <video controls playsinline preload="metadata">

          <source
            src="assets/09-wspomnienie.mp4"
            type="video/mp4"
          >

        </video>

      </div>

    </section>


    <!-- LIST -->

    <section class="letter" id="list">

      <div class="letter-inner reveal">

        <p class="eyebrow">
          05 / DLA CIEBIE
        </p>


        <div class="envelope" id="envelope">

          <div class="envelope-back"></div>


          <div class="letter-paper">

            <p class="letter-small">
              dla Zuzi
            </p>

            <h2>
              Hej, Zuzia.
            </h2>

            <p>
              Nie wiem, ile jeszcze zdjęć zrobimy,
              ile razy będziemy się śmiać z tych samych głupot
              i ile miejsc razem odwiedzimy.
            </p>

            <p>
              Ale wiem jedno — chcę być obok,
              kiedy będziemy tworzyć kolejne wspomnienia.
            </p>

            <p class="signature">
              Twój Czarek ♥
            </p>

          </div>


          <button class="open-letter" id="openLetter">
            Otwórz list
          </button>

        </div>

      </div>

    </section>


    <!-- ZAKOŃCZENIE -->

    <section class="finale">

      <p class="eyebrow">
        I TO DOPIERO POCZĄTEK
      </p>

      <h2>
        Nasza historia<br>
        <i>ciągle się pisze.</i>
      </h2>

      <div class="big-heart">
        ♥
      </div>

      <p>
        01.12.2023 → ∞
      </p>

    </section>

  </main>


  <footer>
    zrobione z miłością · Zuzia & Czarek
  </footer>


  <script src="script.js"></script>

</body>
</html>
