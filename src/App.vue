<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div class="middle">
    <img class="logo" src="DSC_0496.JPG"/>
  </div>

  <div>
    <h2>Nur Amal Yasarah binti Awang Yahya</h2>
    <p>21FTT1283</p>
    <p>Level 5 Diploma in Web Development</p>
  </div>
</template>


<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
.middle {
  display: flex;
  justify-content: center;
}

h2 {
  font-size: 1.5em;
  line-height: 1.1;
  font-weight: bold;
}
</style>