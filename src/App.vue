<template>
  <ion-app>
    <menu-left />
    <router-view />
    <ion-menu-controller></ion-menu-controller>
    <ion-modal-controller></ion-modal-controller>
  </ion-app>

</template>


<style src='@ionic/core/css/core.css'></style>
<style src='@ionic/core/css/ionic.bundle.css'></style>

<script>
import MenuLeft from "./components/menus/MenuLeft";
export default {
  name: "app",
  components: { MenuLeft }
};
</script>


<style>
#app {
  /* font-family: 'Avenir', Helvetica, Arial, sans-serif;
              -webkit-font-smoothing: antialiased;
              -moz-osx-font-smoothing: grayscale; */
}
</style>
