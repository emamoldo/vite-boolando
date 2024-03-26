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
  <!-- FontAwesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"
    integrity="sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
    crossorigin="anonymous" referrerpolicy="no-referrer" />

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
/* Css page */
* {
  margin: 0;
  padding: 0;
}
</style>