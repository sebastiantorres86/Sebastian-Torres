
<body>
  <div class="container">
    <header class="flex-row margin-top margin-bottom">
      <div class="flex-small">
        <img class="logo" src="/images/logo.svg" alt="">
      </div>

      <nav class="flex-small text-right">
        <a href="#Home">Home</a>
        <a href="#Portfolio">Portfolio</a>
        <a href="#About Me">Contact Me</a>
      </nav>
    </header>
    <!--Header Section-->

    <section class="hero margin-top margin-bottom">
      <!-- Include an image for the background -->
      <div class="flex-row copy-container">
        <div class="flex-small one-third copy-content">
          <h1>Hey, I'm Sebastian Torres and I love building beautiful websites</h1>
          <!--In the future this copy should be animated-->

          <a href="#about-me">
            <button class="accent-button square-button no-margin-bottom">
              <i class="fas fa-angle-double-down"></i>
              About Me
            </button>
          </a>

        </div>
      </div>
    </section>
    <!---Hero Section-->

    <section id="about-me" class="about-me margin-top margin-bottom">
      <div class="flex-row space-between">
        <div class="flex-small">
          <img class="responsive-image" src="/images/me.jpeg" alt="">
        </div>
        <div class="flex-small">
          <hr>
          <h2 class="copy-about">About Me</h2>
          <p class="copy-about">I'm a junior front-end developer lookinng for a new role in an exciting company. I
            focus on writing
            accesible HTML,
            using modern CSS practices and writing clean JavaScript. When writing JavaScript code, I mostly use
            React,
            but I can
            adapt to whatever tools are required. I'm based in Mar del Plata, Argentina, but I'm happy working
            remotely and I am
            willing to move to a new location if necessary, even in another country. When I'm not coding, you'll
            find me
            outdoors.
            I love being out in nature whether that's going for a walk, or run. I'd love you to check out my work.
          </p>

          <a href="#Portfolio"><button class="muted-button square-button copy-a">
              Go to Portfolio
            </button></a>
          <hr>
        </div>

      </div>
    </section>
    <!--About Me Section-->

    <section class="call-to-action margin-top margin-bottom">
      <div class="flex-row space-between">
        <div class="flex-small one-third">
          <h2>Interested in doing a project togheter?</h2>
        </div>
        <div class="flex-small one-third vertical-center">
          <nav>
            <a href="#Contact-Me"><button class="muted-button square-button">Contact Me</button></a>
          </nav>
        </div>

      </div>
    </section>
    <!--Call To Action Section-->

  </div>

  <footer class="footer">
    <div class="container padding-top margin-top padding-bottom flex-row space-between">
      <div class="flex-small one-third">
        <img class="logo" src="/images/logo-footer.svg" alt="">
      </div>

      <nav class="flex-small one-third">
        <a href="#Home">Home</a>
        <a href="#Portfolio">Portfolio</a>
        <a href="#About Me">Contact Me</a>
      </nav>

      <nav class="flex-small one-third">
        <a href="#Github">
          <i class="fab fa-github fa-2x"></i>
        </a>
        <a href="#Twitter">
          <i class="fab fa-twitter fa-2x"></i>
        </a>
        <a href="#Linkedin">
          <i class="fab fa-linkedin fa-2x"></i>
        </a>
      </nav>

    </div>
    <!--Footer-->
  </footer>
