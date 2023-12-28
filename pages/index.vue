<template>
  <div>
    <div class="top-page">
    <h1>Ryoichi</h1>
    <p>そこら辺にいる中学生が作ったポートフォリオサイト</p>

    </div>
    <div class="skill">
      <h1>SKILL</h1>
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
  margin-top: 100px;
  margin-bottom: 100px;
}

.skill {
  height: 200px;
  background-color: rgb(255, 255, 255);
  text-align: center;
}
</style>
