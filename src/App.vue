<!-- 
app
- startseite
  - start session
  - join 
- session screen
  - ticket-name
  - user estimate form
  - statistic
    - admin:
-->
<template>
  <div id="app">
    <img id="logo" alt="Vue logo" src="./assets/heart.webp">
    <HelloWorld msg="Hallo, Sabrina!"/>
    <div>
      <button type="submit" name="create-sesion">Neue Session starten</button>
      <hr />
        <div class="estimate-secreen">
          <!-- <input  type="text">zcpm-1234</input> -->
        </div>
      <hr />
    </div>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

#logo {
  height: 100px;
}
</style>
