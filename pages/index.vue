<template>
  <div>
    <div class="top-page">
    <h1>Ryoichi</h1>
    <p>そこら辺にいる中学生が作ったポートフォリオサイト</p>

    </div>
    <div class="skill">
      <h1>SKILL</h1>
      <img class="html" src="/HTML-LOGO.png">
      <img class="css" src="/CSS-LOGO.png">
      <img class="javascript" src="/javascript-logo.svg">
      <img class="nuxt" src="/Nuxt_log.png">
      <img class="ruby" src="/Ruby_logo.png">
      <img class="rails" src="/Rails_Logo.png">
    </div>
    <nuxt-link to="/projects">View Projects</nuxt-link>
    <nuxt-link to="/contact">Contact Me</nuxt-link>
  </div>
</template>

<script>
export default {
  name: 'Index',
}
</script>

<style scoped>
div {

}

img {
  height: 40%;
}

.html {
  padding-right: 20px;
}

.css {
  padding-right: 20px;
}

.javascript {
  padding-right: 20px;
}

.top-page {
  text-align: center;
  margin-top: 150px;
  margin-bottom: 150px;
}

.skill {
  height: 200px;
  background-color: rgba(230, 230, 230, 0.767);
  text-align: center;
}
</style>
