<template>
  <div id="app">
    <navbarComponent></navbarComponent>
    <breadCrumbComponent></breadCrumbComponent>
    <galleryComponent></galleryComponent>
    <cardComponent></cardComponent>
    <sliderComponent></sliderComponent>
    <footerComponent></footerComponent>
    <copyrightComponent></copyrightComponent>

  </div>
</template>

<script>
import navbarComponent from "./components/navbarComponent.vue"
import breadCrumbComponent from "./components/breadCrumbComponent.vue"
import galleryComponent from "./components/galleryComponent.vue"
import cardComponent from "./components/cardComponent.vue"
import sliderComponent from "./components/sliderComponent.vue"
import footerComponent from "./components/footerComponent.vue"
import copyrightComponent from "./components/copyrightComponent.vue"

export default {
  name: 'App',
  components: {
    navbarComponent,
    breadCrumbComponent,
    galleryComponent,
    sliderComponent,
    cardComponent,
    footerComponent,
    copyrightComponent,
  }
}  
</script>

<style>
.border-rounded {
  border-radius: 20px;
}
.bg-pink {
  background-color: pink;
}
.bg-grey {
  background-color: darkgrey;
}
</style>