<template>
  <section class="container">
    <div>
      <OctahedronSpin/>
      <h1 class="title">
        RICHARD MICHELS
      </h1>
      <h2 class="subtitle">
        developer
      </h2>
      <div class="links">
        <a href="/about" class="link">About</a>
        <!-- <a href="https://github.com/nuxt/nuxt.js" target="_blank" class="button--grey">GitHub</a> -->
      </div>
    </div>
  </section>
</template>

<script>
import OctahedronSpin from './../components/OctahedronSpin.vue'

export default {
  components: {
    OctahedronSpin
  }
}
</script>

<style>
.container
{
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
.title
{
  font-family: "Quicksand", "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif; /* 1 */
  display: block;
  font-weight: 300;
  font-size:75px;
  color: #35495e;
  letter-spacing: 1px;
}
.subtitle
{
  font-weight: 300;
  font-size: 35px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}
.links
{
  padding-top: 15px;
}
.link{
  transform: translateX(-50%);
  color: #35495e;
}
.octahedron
{
  position:absolute;
  top:-100px;
  left:-100px;
}
</style>
