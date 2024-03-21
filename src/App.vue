<script>
// js page
</script>


<template>
  <!-- html page -->

  <body>
    <!--  Page Header  -->
    <header>
      <div class="list">
        <div class="left_menu">
          <div>Uomo</div>
          <div>Donna</div>
          <div>Bambini</div>
        </div>

        <img class="logo" src="./assets/img/boolean-logo.png" alt="">

        <div class="right_menu">
          <div>
            <i class="fa-regular fa-user"></i>
          </div>

          <div>
            <i class="fa-regular fa-heart"></i>
          </div>

          <div>
            <i class="fas fa-shopping-bag"></i>
          </div>
        </div>

      </div>
    </header>
    <!-- /Page Header  -->

    <!--  Site Main  -->
    <div class="top_container">
      <ul class="relaxed_fit">
        <li>
          <img class="photo" src="./assets/img/1.webp" alt="">

          <div class="hover1">
            <img class="photo" src="./assets/img/1b.webp" alt="">
            <p>Levi's</p>
            <strong>RELAXED FIT TEE UNISEX</strong>
            <span class="discount_price">14.99€ <span class="normal_price">29.99€</span></span>
          </div>

          <div class="text">
            <p>Levi's</p>
            <strong>RELAXED FIT TEE UNISEX</strong>
            <span class="discount_price">14.99€ <span class="normal_price">29.99€</span></span>
          </div>
        </li>
      </ul>

      <ul class="roses_tee">
        <li>
          <img class="photo" src="./assets/img/2.webp" alt="">

          <div class="hover1">
            <img class="photo" src="./assets/img/2b.webp" alt="">
            <p>Guess</p>
            <strong>ROSES TEE</strong>
            <span class="discount_price">20.99€ <span class="normal_price">29.99€</span></span>
          </div>

          <div class="text">
            <p>Guess</p>
            <strong>ROSES TEE</strong>
            <span class="discount_price">20.99€ <span class="normal_price">29.99€</span></span>
          </div>
        </li>
      </ul>

      <ul class="sugar">
        <li>
          <img class="photo" src="./assets/img/3.webp" alt="">

          <div class="hover1">
            <img class="photo" src="./assets/img/3b.webp" alt="">
            <p>Come Zucchero Filato</p>
            <strong>VOGLIA DI COLORI PASTELLO</strong>
            <span class="discount_price">129.99€ <span class="normal_price">184.99€</span></span>
          </div>

          <div class="text">
            <p>Come Zucchero Filato</p>
            <strong>VOGLIA DI COLORI PASTELLO</strong>
            <span class="discount_price">129.99€ <span class="normal_price">184.99€</span></span>
          </div>
        </li>
      </ul>
    </div>

    <div class="bottom_container">
      <ul class="tee_unisex">
        <li>
          <img class="photo" src="./assets/img/4.webp" alt="">

          <div class="hover1">
            <img class="photo" src="./assets/img/4b.webp" alt="">
            <p>Levi's</p>
            <strong>TEE UNISEX</strong>
            <span class="discount_price">14.99€ <span class="normal_price">29.99€</span></span>
          </div>

          <div class="text">
            <p>Levi's</p>
            <strong>TEE UNISEX</strong>
            <span class="discount_price">14.99€ <span class="normal_price">29.99€</span></span>
          </div>
        </li>
      </ul>

      <ul class="stripe">
        <li>
          <img class="photo" src="./assets/img/5.webp" alt="">

          <div class="hover1">
            <img class="photo" src="./assets/img/5b.webp" alt="">
            <p>Maya Deluxe</p>
            <strong>STRIPE BODICE</strong>
            <span class="discount_price">99.99€</span>
          </div>

          <div class="text">
            <p>Maya Deluxe</p>
            <strong>STRIPE BODICE</strong>
            <span class="discount_price">99.99€</span>
          </div>
        </li>
      </ul>

      <ul class="maglione">
        <li>
          <img class="photo" src="./assets/img/6.webp" alt="">

          <div class="hover1">
            <img class="photo" src="./assets/img/6b.webp" alt="">
            <p>Esprit</p>
            <strong>MAGLIONE - NERO</strong>
            <span class="discount_price">29.99€</span>
          </div>

          <div class="text">
            <p>Esprit</p>
            <strong>MAGLIONE - NERO</strong>
            <span class="discount_price">29.99€</span>
          </div>
        </li>
      </ul>
    </div>
    <!-- /Site Main  -->

    <!--  Site Footer -->
    <footer>
      <div class="footer">
        <h2>Booleando S.r.l.</h2>
        <div class="text_footer">
          <p>Informazioni Legali</p>
          <p>Informativa sulla privacy</p>
          <p>Diritto di recesso</p>
        </div>
      </div>

      <div class="right">
        <h4>Trovaci su</h4>
        <a href="#">
          <i class="fab fa-twitter fa-xs"></i>
        </a>
        <a href="#">
          <i class="fab fa-facebook fa-xs"></i>
        </a>
        <a href="#">
          <i class="fab fa-instagram fa-xs"></i>
        </a>
        <a href="#">
          <i class="fab fa-pinterest fa-xs"></i>
        </a>
        <a href="#">
          <i class="fab fa-youtube fa-xs"></i>
        </a>
      </div>

    </footer>
    <!-- /Site Footer -->
  </body>
</template>





<style>
/* css page */
* {
  margin: 0;
  padding: 0;
}

/* Color Palette */
:root {
  --bool-header: #ff6900;
  --bool-backg-photo: #eeefee;
  --bool-footer: #1b1b1a;
  --bool-header-text: #ffffff;
  --bool-sost-text: #018100;
  --bool-disc-text: #fe0100;
}

/* Site Header */
.list {
  max-width: 1920px;
  height: 70px;
  background-color: var(--bool-header);
  display: flex;
  justify-content: space-around;
  align-items: center;
}

.left_menu,
.right_menu {
  display: flex;
  color: var(--bool-header-text);
  gap: 2rem;
}

.left_menu {
  margin-left: 10rem;
}

.right_menu {
  margin-right: 10rem;
}

.logo {
  display: flex;
  align-self: center;
  width: 150px;
}

/* /Site Header */

/* Site Main */
.top_container,
.bottom_container {
  width: 1000px;
  margin: 0 auto;
  display: flex;
  justify-content: space-evenly;
}

ul {
  list-style: none;
}

.photo {
  height: 400px;
  width: auto;
  padding-top: 3rem;

}

.text {
  display: flex;
  flex-direction: column;
}

.discount_price {
  color: var(--bool-disc-text);
}

.normal_price {
  color: black;
}


/* Footer Page */
footer {
  margin-top: 2rem;
  height: 100px;
  display: flex;
  align-items: center;
  background-color: var(--bool-footer);
  gap: 70rem;
}

.footer {
  margin: 0;
  margin-left: 10rem;
  color: var(--bool-header-text);
  display: flex;
  flex-direction: column;
}

.text_footer {
  display: flex;
  gap: 1rem;
}

.right {
  color: var(--bool-header-text);
}

.hover1 {
  display: none;
}

:hover+.hover1 {
  display: block;

}
</style>
