<template>
  <div class="container">

    <Mainmenu />
    <router-view />
  </div>
</template>
<script>
import Mainmenu from "@/components/navbar/Mainmenu.vue";
const components = {
  Mainmenu
};
export default{
  components,
  }




</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

#nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;


    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>
