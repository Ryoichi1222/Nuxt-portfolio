<template>
  <div>
    <div class="top-page">
    <h1>Ryoichi</h1>
    <p>そこら辺にいる中学生が作ったポートフォリオサイト</p>
    </div>
    <div class="about">
      <h1>About</h1>
    </div>
    <div class="skill">
      <h1>SKILL</h1>
      <img class="html" src="/HTML-LOGO.png">
      <img class="css" src="/CSS-LOGO.png">
      <img class="javascript" src="/javascript-logo.svg">
      <br>
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
.top-page {
  text-align: center;
  margin-top: 170px;
  margin-bottom: 170px;
}

.about {
  margin-top: 100px;
  margin-bottom: 100px;
}



.skill {
  height: 400px;
  background-color: rgba(230, 230, 230, 0.767);
  text-align: center;
}

.skill h1 {
  line-height: 70px;
}

.skill img {
  height: 30%;
}

.html {
  padding-right: 60px;
}

.css {
  padding-right: 60px;
}

.javascript {
  padding-right: 60px;
}
.nuxt {
  padding-right: 20px;
}

.ruby {
  padding-right: 20px;
}

.rails {
  padding-right: 20px;
}




</style>
