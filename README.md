# 20924713_Andara_Sf_Ecomerce_UAS<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Lynx.Store</title>

    <!--Fonts-->
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
      rel="stylesheet"
    />

    <!--feather icons-->
    <script src="https://unpkg.com/feather-icons"></script>

    <!--my style-->
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <!--navbar-->
    <nav class="navbar">
      <a href="#" class="navbar-logo">Lynx<span>Store.Coffee</span></a>

      <div class="navbar-nav">
        <a href="#home">Home</a>
        <a href="#about">Tentang kami</a>
        <a href="#menu">Menu</a>
        <a href="#contact">Kontak</a>
      </div>

      <div class="navbar-extra">
        <a href="#" id="search"><i data-feather="search"></i></a>

        <a href="#" id="shopping-cart"><i data-feather="shopping-cart"></i></a>

        <a href="#" id="produk-menu"><i data-feather="menu"></i></a>
      </div>
    </nav>
    <!--navbar end-->

    <!--hero section-->
    <section class="hero" id="home">
      <main class="content">
        <h1>Teman setia di setiap<span>Tegukan</span></h1>
        <p>Karena setiap cangkir punya cerita</p>
        <p>
          <a href="#" class="cta">Beli Sekarang</a>
        </p>
      </main>
    </section>
    <!--end hero section-->

    <!--about section-->
    <section id="about" class="about">
      <h2><span>Tentang</span>Kami</h2>

      <div class="row">
        <div class="about-img">
          <img src="img/tentang-kami.jpg"Tentang Kami />
        </div>
        <div class="content">
          <h3>Kenapa Harus LynxStore.Coffee</h3>
          <p>
            LynxStore.Coffee menyajikan biji kopi berkualitas dari biji kopi pilihhan yang diproses dengan penuh cinta, menghasilkan rasa yang autentik dan aroma yang memikat. Dari ekspreso pekat, latte lembut sampai kopi manual brew yanng kaya rasa, semua dibuat untuk menunjukan lidah dan menghangatkan hati
          </p>
          <p>
            Teman setia di setiap tegukan.
            Kami menghadirkan pengalaman ngopi yang lebih dari sekadar minum kopi. Setiap biji kopi kami dipilih dari perkebunan terbaik, di-roasting dengan tepat, dan diracik oleh barista berpengalaman untuk menghasilkan rasa yang sempurna di setiap cangkir.
          </p>
        </div>
      </div>
    </section>
    <!--end about section-->

    <!--menu section-->
    <section id="menu" class="menu">
      <h2><span>Menu</span>Kami</h2>
      <p>Nikmati pengalaman meminum kopi terbaik anda</p>

      <div class="row">

        <div class="menu-card gap-4">
          <img src="img/MENU/1 (2).JPG" alt="Latte">
          <h3 class="menu-card-title">-Latte-</h3>
          <p class="menu-card-price">IDR 33K</p>
        </div>
       
        <div class="menu-card gap-4">
          <img src="img/MENU/2.jpg" alt="Amerikano">
          <h3 class="menu-card-title">-Amerikano-</h3>
          <p class="menu-card-price">IDR 33K</p>
        </div>

        <div class="menu-card gap-4">
          <img src="img/MENU/3.jpg" alt="Mocachino">
          <h3 class="menu-card-title">-Mocachino-</h3>
          <p class="menu-card-price">IDR 33K</p>
        </div>

        <div class="menu-card gap-4">
          <img src="img/MENU/4.jpg" alt="Capuccino">
          <h3 class="menu-card-title">-Capuccino-</h3>
          <p class="menu-card-price">IDR 33K</p>
        </div>

        <div class="menu-card gap-4">
          <img src="img/MENU/4.jpg" alt="Luwak">
          <h3 class="menu-card-title">-Luwak-</h3>
          <p class="menu-card-price">IDR 33K</p>
        </div>

        <div class="menu-card gap-4">
          <img src="img/MENU/6.jpg" alt="Espresso">
          <h3 class="menu-card-title">-Espresso-</h3>
          <p class="menu-card-price">IDR 33K</p>
        </div>

       

      </div>
    </section>
    <!--menu section end-->

<!-- conntact section star-->
<section id="contact" class="contact">
  <section id="menu" class="menu">
    <h2><span>Kontak</span>Kami</h2>
    <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Minima, obcaecati?</p>

    <div class="row">
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d126748.56400422927!2d107.56075474693867!3d-6.9034423792835!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e68e6398252477f%3A0x146a1f93d3e815b2!2sBandung%2C%20Kota%20Bandung%2C%20Jawa%20Barat!5e0!3m2!1sid!2sid!4v1752236316711!5m2!1sid!2sid"  allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade" class="map"></iframe>

      <form action="">
        <div class="input-group">
          <i data-feather="user"></i>
          <input type="text" placeholder="nama">
        </div>
        <div class="input-group">
          <i data-feather="mail"></i>
          <input type="text" placeholder="email">
        </div>
        <div class="input-group">
          <i data-feather="phone"></i>
          <input type="text" placeholder="no hp">
        </div>
        <button type="submit" class="button">Kirim pesan</button>
      
      </form>


    </div>
</section>
<!-- end conntact section-->

<!--footer-->
<footer>

  <div class="creadit">
    <p>Created by <a>AndaraShaka</a>.&copy;2025.</p>
  </div>
</footer>
<!--end footer-->







    <!--feather icons-->
    <script>
      feather.replace();
    </script>

    <!--my java script-->
    <script src="js/script.js"></script>
  </body>
</html>

:root {
  --primary: #9b8b2d;
  --bg: #000000;
}

* {
  font-family: "Poppins", sans-serif;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  outline: none;
  border: none;
  text-decoration: none;
}

body {
  font-family: "Poppins", sans-serif;
  background-color: var(--bg);
  color: #ffffff;

}

/* Navbar */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 1.4rem 7%;
  background-color: rgba(1, 1, 1, 0.8);
  border-bottom: 1px solid #000000;
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 9999;
}
.navbar .navbar-logo {
  font-size: 2rem;
  font-weight: 700;
  color: #ffffff;
  font-style: italic;
}

.navbar .navbar-logo span {
  color: var(--primary);
}

.navbar .navbar-nav a {
  color: #ffffff;
  display: inline-block;
  font-size: 1.3rem;
  margin: 0 1rem;
}

.navbar .navbar-nav a:hover {
  color: var(--primary);
}

.navbar .navbar-nav a:after {
  content: "";
  display: block;
  padding-bottom: 0.5rem;
  border-bottom: 0.1rem solid var(--primary);
  transform: scaleX(0);
  transition: 0.2s linear;
}

.navbar .navbar-nav a:hover::after {
  transform: scaleX(0.5);
}

.navbar .navbar-extra a {
  color: #ffffff;
  margin: 0 0.5rem;
}

.navbar .navbar-extra a:hover {
  color: #010101;
}

#produk-menu {
  display: none;
}

/* hero section */
.hero {
  min-height: 100vh;
  display: flex;
  align-items: center;
  background-image: url("https://images.unsplash.com/photo-1630411870702-8f6f8fd80ce2?q=80&w=1332&auto=format&fit=crop&ixlib=rb-4.1.0&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center;
  position: relative;
}

.hero::after {
  content: "";
  display: block;
  position: absolute;
  width: 100%;
  height: 30%;
  bottom: 0;
  background: linear-gradient(
    0deg,
    rgba(1, 1, 3, 1) 8%,
    rgba(255, 255, 255, 0) 50%
  );
}

.hero .content {
  padding: 1.4rem 7%;
  max-width: 60rem;
}

.hero .content h1 {
  font-size: 5em;
  color: #fff;
  text-shadow: 1px 1px 3px rgba(1, 1, 3, 0.5);
  line-height: 1.2;
}

.hero .content h1 span {
  color: var(--primary);
}

.hero .content p {
  font-size: 1.6rem;
  margin-top: 1rem;
  line-height: 1.4;
  font-weight: 100;
  text-shadow: 1px 1px 3px rgba(1, 1, 3, 0.5);
  mix-blend-mode: none;
}

.hero .content .cta {
  margin-top: 1rem;
  display: inline-block;
  padding: 1rem 3rem;
  font-size: 1.4rem;
  color: #fff;
  background-color: var(--primary);
  border-radius: 0.5rem;
  box-shadow: 1px 1px 3px rgba(1, 1, 3, 0.5);
}

/* about section */
.about, .menu {
  padding: 5rem 7% 1.4rem;
}

.about h2, .menu h2 {
  text-align: center;
  font-size: 2.6rem;
  margin-bottom: 3rem;
}

.about h2 span, .menu h2 span {
  color: var(--primary);
}

.about .row {
  display: flex;
}

.about .row .about-img {
  flex: 1 1 30rem;
}

.about .row .about-img {
  width: 100%;
}

.about .row .content {
  flex: 1 1 35rem;
  padding: 0 1rem;
}

.about .row .content h3 {
  font-size: 1.8rem;
  margin-bottom: 1rem;
}

.about .row .content p {
  margin-bottom: 0.8rem;
  font-size: 1.3rem;
  font-weight: 100;
  line-height: 1.6;
}

/*menu section*/
.menu h2 {
  margin-bottom: 1rem;
}
.menu p {
  text-align: center;
  max-width: 30rem;
  margin: auto;
  font-weight: 100;
  line-height: 1.5;
}

.menu .row {
  display: flex;
  flex-wrap: wrap;
  margin-top: 5rem;
  justify-content: center;
}

.menu .row .menu-card {
  text-align: center;
}

.menu .row .menu-card img {
border-radius: 40%;
width: 40%;
}

.menu .row .menu-card .menu-card-tittle {
  margin: 1.5rem auto 0.5rem;
}




/* kontak sectionn */

.contact {
  padding: 5rem 7% 1.3rem;
}

.contact h2 {
  text-align: center;
  font-size: 2.6rem;
  margin-bottom: 1rem;
}

.contact h2 span {
  color: var(--primary);
}

.conntact p {
  text-align: center;
  max-width: 30rem;
  margin: auto;
  font-weight: 100;
  line-height: 1.6;
}

.contact .row {
  display: flex;
  margin-top: 2rem;
  background-color: #222;
}

.contact .row .map {
  flex: 1 1 45rem;
  width: 100%;
  object-fit: cover;
}

.contact .row form {
  flex: 1 1 45rem;
  padding: 5rem 2rem;
  text-align: center;
}

.contact .row form .input-group {
  display: flex;
  align-items: center;
  margin-top: 2rem;
  background-color: var(--bg);
  border: 1px solid #eee;
  padding-left: 2rem;
}

.contact .row form .input-group input {
  width: 100%;
  padding: 2rem;
  font-size: 1.7rem;
  background: none;
}

.contact .row form .button {
  margin-top: 3rem;
  display: inline-block;
  padding: 1rem 3rem;
  font-size: 1.7rem;
  color: #fff;
  background-color: var(--primary);
  cursor: pointer;
}

/*footer*/

footer {
  background-color: #9b8b2d;
  text-align: center;
  padding: 1rem 0;
  margin-top: 3rem;
}


/*end footer*/

/* media queries */

/* Laptop */
@media (max-width: 1366px) {
  html {
    font-size: 75%;
  }

  .contact .row {
    display: flex;
    margin-top: 2rem;
    background-color: #222;
  }

  .contact .row .map {
    flex: 1 1 45rem;
    width: 100%;
    object-fit: cover;
  }

  .contact .row form {
    flex: 1 1 45rem;
    padding: 5rem 2rem;
    text-align: center;
  }

  .contact .row form .input-group {
    display: flex;
    align-items: center;
    margin-top: 2rem;
    background-color: var(--bg);
    border: 1px solid #eee;
    padding-left: 2rem;
  }

  .contact .row form .input-group input {
    width: 100%;
    padding: 2rem;
    font-size: 1.7rem;
    background: none;
  }

  .contact .row form .button {
    margin-top: 3rem;
    display: inline-block;
    padding: 1rem 3rem;
    font-size: 1.7rem;
    color: #fff;
    background-color: var(--primary);
    cursor: pointer;
  }
}

/* tablet */
@media (max-width: 768px) {
  html {
    font-size: 62%;
  }

  #produk-menu {
    display: inline-block;
  }

  .navbar .navbar-nav {
    position: absolute;
    top: 100%;
    right: -100%;
    background-color: #fff;
    width: 30rem;
    height: 100vh;
    transition: 0.4s;
  }

  .navbar .navbar-nav.active {
    right: 0;
  }

  .navbar .navbar-nav a {
    color: var(--bg);
    display: block;
    margin: 1.5rem;
    padding: 0.5rem;
    font-size: 2rem;
  }

  .navbar .navbar-nav a::after {
    transform-origin: 0 0;
  }

  .navbar .navbar-nav a:hover::after {
    transform: scaleX(0.2);
  }

  .about .row {
    flex-wrap: wrap;
  }

  .about .row .about-img img {
    height: 24rem;
    object-fit: cover;
    object-position: center;
  }

  .about .row .content {
    padding: 0;
  }

  .about .row .content h3 {
    margin-top: 1rem;
    font-size: 2rem;
  }

  .about .row .content p {
    font-size: 1.6rem;
  }

  .menu p {
    font-size: 1.2rem;
  }
}

/* mmedia phone */
@media (max-width: 450px) {
  html {
    font-size: 55%;
  }
}
