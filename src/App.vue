<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
  name: 'App',

  components: {
    AppHeader,
    AppMain,
    AppFooter,
  }
}
</script>


<template>

  <body>
    <!--  Page Header  -->
    <AppHeader />
    <!-- /Page Header  -->

    <!--  Site Main  -->
    <AppMain />
    <!-- /Site Main  -->

    <!--  Site Footer -->
    <AppFooter />
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