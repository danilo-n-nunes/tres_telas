<template>
  <div id="app">
    <navbar-component />
    <side-bar-component />
  </div>
</template>

<script>
import NavbarComponent from './components/NavbarComponent.vue'
import SideBarComponent from './components/SideBarComponent.vue'

export default {
  name: 'App',
  components: {
    NavbarComponent,
    SideBarComponent
  }
}
</script>

<style>

</style>
