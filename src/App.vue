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

/* /Site Header */



/* Site Main */

/* /Site Main */



/*  Footer Page */
/* /Site Footer */
</style>