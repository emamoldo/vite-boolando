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
/* Css page */
* {
  margin: 0;
  padding: 0;
}
</style>