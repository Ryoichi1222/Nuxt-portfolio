<template>
  <div>
    <div class="top-page">
    <h1>Ryoichi</h1>
    <p>そこら辺にいる中学生が作ったポートフォリオサイト</p>

    </div>
    <div class="skill">
      <h1>SKILL</h1>
      <img src="/HTML-LOGO.png">
      <img src="/CSS-LOGO.png">
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
  padding-right: 10px;
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
