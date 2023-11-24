<!doctype html>
<html lang="en">

<head>
  <title>Stylish Steps</title>
  <!-- Required meta tags -->
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

  <!-- Bootstrap CSS v5.2.1 -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css" rel="stylesheet"
    integrity="sha384-iYQeCzEYFbKjA/T2uDLTpkwGzCiq6soy8tYaI1GyVh/UjpbCx/TYkiZhlZB6+fzT" crossorigin="anonymous">
  <link rel="stylesheet" href="css/home.css">
  <link rel="icon" href="img/sneaker.png" type="image/x-icon">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Cabin:ital,wght@1,600&display=swap" rel="stylesheet">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link
    href="https://fonts.googleapis.com/css2?family=Kanit:ital,wght@1,600&family=Smooch+Sans&family=Ubuntu:ital,wght@1,500&display=swap"
    rel="stylesheet">
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link
    href="https://fonts.googleapis.com/css2?family=Exo:ital@1&family=Kanit:ital@1&family=Kdam+Thmor+Pro&display=swap"
    rel="stylesheet">
</head>

<body>
  <main>
    <header>
      <nav class="navbar navbar-expand-lg">
        <div class="container-fluid">
          <a class="navbar-brand" href="home.html"><i class="fa-solid fa-shoe-prints"
              style="color: #ffffff;"></i>&nbsp;STYLISH STEPS</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown"
            aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
            <i class="fa-solid fa-bars" style="color: #787ff6;"></i>
          </button>
          <div class="collapse navbar-collapse" id="navbarNavDropdown">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link" aria-current="page" href="home.html">HOME</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" onclick="catalogPage()">CATALOG</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="contact.html">CONTACT US</a>
              </li>
              <li class="nav-item dropdown">
                <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button"
                  data-bs-toggle="dropdown" aria-expanded="false">
                  SOCIAL LINKS
                </a>
                <ul class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                  <li><a class="dropdown-item" href="#"><i class="fa-brands fa-instagram" style="color: #787ff6;"></i>
                      Instagram</a></li>
                  <li><a class="dropdown-item" href="#"><i class="fa-brands fa-facebook" style="color: #787ff6;"></i>
                      Facebook</a></li>
                  <li><a class="dropdown-item" href="#"><i class="fa-brands fa-tiktok" style="color: #787ff6;"></i>
                      TikTok</a></li>
                </ul>
              </li>
            </ul>
            <button id="signIn" class="nav-link signInBtn" onclick="signinPage()">SIGN IN</button>

          </div>

        </div>
      </nav>
    </header>

    <section class="container-cont">
      <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <span>Black Friday Sale | Save Up to 60%</span>
          </div>

          <div class="carousel-item">
            <span>Black Friday Featured Offer</span><br>
            <a href="">Shop Now</a>
          </div>
        </div>
      </div>


      <div class="slider" x-data="{start: true, end: false}" style="padding-top: 100px;">
        <div class="slider__content" x-ref="slider"
          x-on:scroll.debounce="$refs.slider.scrollLeft == 0 ? start = true : start = false; Math.abs(($refs.slider.scrollWidth - $refs.slider.offsetWidth) - $refs.slider.scrollLeft) < 5 ? end = true : end = false;">
          <div class="slider__item">
            <img class="slider__image" src="img/sneaker1.png" alt="Image">
            <div class="slider__info">
              <h2>Nike Blazer Mid <br> '77 Vintage</h2>
            </div>
          </div>
          <div class="slider__item">
            <img class="slider__image" src="img/sneaker2.png" alt="Image">
            <div class="slider__info">
              <h2>Nike SB Nyjah <br> 3 Premium</h2>
              <p></p>
            </div>
          </div>
          <div class="slider__item">
            <img class="slider__image" src="img/sneaker3.png" alt="Image">
            <div class="slider__info">
              <h2>Nike SB <br> Force 58</h2>
            </div>
          </div>
          <div class="slider__item">
            <img class="slider__image" src="img/sneaker4.png" alt="Image">
            <div class="slider__info">
              <h2>Adidas Samba <br> OG White</h2>
            </div>
          </div>
          <div class="slider__item">
            <img class="slider__image" src="img/sneaker5.png" alt="Image">
            <div class="slider__info">
              <h2>Nike Air Force 1 07 LV8 <br> 'What The LA'</h2>
            </div>
          </div>
          <div class="slider__item">
            <img class="slider__image" src="img/sneaker6.png" alt="Image">
            <div class="slider__info">
              <h2>Polo Ralph Lauren</h2>
            </div>
          </div>
          <div class="slider__item">
            <img class="slider__image" src="img/sneaker7.png" alt="Image">
            <div class="slider__info">
              <h2>Balenciaga</h2>
            </div>
          </div>
          <div class="slider__item">
            <img class="slider__image" src="img/sneaker8.png" alt="Image">
            <div class="slider__info">
              <h2>Nike Air Jordan 1 <br> High Element <br> GORE-TEX Sky J</h2>
            </div>
          </div>
          <div class="slider__item">
            <img class="slider__image" src="img/sneaker9.png" alt="Image">
            <div class="slider__info">
              <h2>Nike Dunk Low <br> Vintage Panda</h2>
            </div>
          </div>
          <div class="slider__item">
            <img class="slider__image" src="img/sneaker10.png" alt="Image">
            <div class="slider__info">
              <h2>New Balance <br> Numeric White/Red</h2>
            </div>
          </div>
        </div>
      </div>
      <button id="buyNowBtn" class="buyBtn" onclick="modalPage()">BUY NOW</button>
      </div>
    </section>
    <div id="myModall" class="modall">
      <div class="modal-content">
        <span class="close-btn" onclick="closeModall()">&times;</span>
        <p>We Apologize <br>
          The page is currently unavailable...</p>
        <img src="img/cat-cute.gif" alt="">
      </div>
      <button onclick="scrollToTop()" id="scroll" class="scrollTop"><i class="fa-solid fa-arrow-up"
          style="color: #000000;"></i></button>

  </main>

  <section class="shop-container">
    <div class="wrap">
      <div class="element-animation">
        <div class="main_content">
          <div class="main_text">
            <h1>NIKE<br><span>Collection</span></h1>
            <p>
              Nike, Inc., American sportswear company that is one of the world’s best-known brands.
              It was founded in 1964 as Blue Ribbon Sports by Phil Knight and Bill Bowerman, his former track-and-field
              coach at the University of Oregon.
              The company was renamed Nike, Inc., in 1971, and it went public in 1980. By the early 21st century,
              Nike had retail outlets and distributors in more than 170 countries, and its logo—a curved check mark
              called the “swoosh”—was recognized throughout the world.
            </p>
            <ul class="list-group">
              <li class="list-group-item"><a href=""></a>Innovative Design</li>
              <li class="list-group-item"><a href=""></a>Comfort</li>
              <li class="list-group-item"><a href=""></a>Athlete Endorsements</li>
            </ul>
          </div>
          <div class="main_image">
            <img src="img/sneaker12.png">
          </div>
        </div>
      </div>
    </div>
    <div id="myModall" class="modall">
      <div class="modal-content">
        <span class="close-btn" onclick="closeModall()">&times;</span>
        <p>We Apologize <br>
          The page is currently unavailable...</p>
        <img src="img/cat-cute.gif" alt="">
  </div>
</div>
</section>
<footer class="bg-light py-3 h-100">
  <img src="img/footer.png" alt="">
  <p>CREATED BY:</p><br>
  <div id="team-members">
    <article class="team-member">
      <img class="team-member-avatar" src="img/pavel.jpg" alt="Park Pavel">
      <div class="team-member-name">
        <h3>Park Pavel</h3>
        <p>Frontend Developer</p>
      </div>
      <ul class="social-links">
        <li><a href="https://www.linkedin.com/in/pavel-park-538863259/"><i class="fa-brands fa-linkedin" style="color: black;"></i></a></li>
        <li><a href="https://github.com/KIYOKATA-1"><i class="fa-brands fa-github" style="color: #000000;"></i></a></li>
      </ul>
    </article>
    <article class="team-member">
      <img class="team-member-avatar" src="img/talgat.jpg" alt="Mukhtarov Talgat">
      <div class="team-member-name">
        <h3>Mukhtarov Talgat</h3>
        <p>Java Developer</p>
      </div>
      <ul class="social-links">
        <li><a href="https://www.linkedin.com/in/talgat-mukhtarov-323436240/"><i class="fa-brands fa-linkedin" style="color: black;"></i></a></li>
        <li><a href="https://github.com/T4jgat"><i class="fa-brands fa-github" style="color: #000000;"></i></a></li>
      </ul>
    </article>
    <article class="team-member">
      <img class="team-member-avatar" src="img/alikhan.jpg" alt="Sayat Alikhan">
      <div class="team-member-name">
        <h3>Sayat Alikhan</h3>
        <p>Backend Developer</p>
      </div>
      <ul class="social-links">
        <li><a href="https://www.linkedin.com/me?trk=p_mwlite_feed_updates-secondary_nav"><i class="fa-brands fa-linkedin" style="color: black;"></i></a></li>
        <li><a href=""><i class="fa-brands fa-github" style="color: #000000;"></i></a></li>
      </ul>

      
      <!-- Modal Box -->
      <div id="fullscreen-modal">
        <span class="close-modal" onclick="closeFullscreenModal()"><i class="fa-solid fa-xmark" style="color: #f0f0f0;"></i></span>
        <img id="fullscreen-image"  class="fullscreen-image" alt="Fullscreen Image">
    </div>
    
    </article>
  </div>
</footer>
  <!-- Bootstrap JavaScript Libraries -->
  <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"
    integrity="sha384-oBqDVmMz9ATKxIep9tiCxS/Z9fNfEXiDAYTujMAeBAsjFuCZSmKbSSUnQlmh/jp3" crossorigin="anonymous">
    </script>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/js/bootstrap.min.js"
    integrity="sha384-7VPbUDkoPSGFnVtYi0QogXtr74QeVeeIs99Qfg5YCF+TidwNdjvaKZX19NZ/e6oz" crossorigin="anonymous">
    </script>

  <script src="js/home.js"></script>
</body>

</html>
