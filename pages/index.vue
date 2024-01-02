<template>
  <div>
    <div class="top-page">
    <h1>Ryoichi</h1>
    <p>そこら辺にいる中学生が作ったポートフォリオサイト</p>
    </div>
    <div class="about">
      <h1>About</h1>
      <div class="explanation">
        <img class="profile-img" src="/Profile.png">
          <div class="right">  
            <p class="title">Ryoichi</p>
            <p class="text">中学校１年の時に始めてプログラミングを学んだ。</p>
            <p class="text">趣味はゲームをしたり、アニメを見たりする事です。</p>
            <p class="text">プロフィールの写真は修学旅行で撮った写真でお気に入りです。</p>
            <p class="text">「僕のSNSリンク」</p>
            <div class="sns-icon">
            <a href="https://twitter.com/Ryo211222"><img class="x-icon" src="/X-icon.png"></a>
            <a href="https://github.com/RyoichiKami"><img class="github-icon" src="/github-mark.png"></a>
            <a href="https://discord.gg/cv6bKDyV"><img class="discord-icon" src="/Discord-icon.png"></a>
          </div>
          </div>  
      </div>
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
.top-page { 
  text-align: center;
  margin-top: 170px;
  margin-bottom: 170px;
}

.about {
  margin-bottom: 100px;
}

.about h1 {
  text-align: center;
  border-bottom: 5px solid #b8e8de;
  padding: 10px;
}

.explanation {
  display: flex;
  padding-top: 100px;
}

.explanation .profile-img {
  width: 20%; /*画像サイズ指定*/
  margin: 0;
  padding: 0;
  border-radius: 50%;
  overflow: hidden;
  position: relative;
  left: 300px;
}

.explanation .right {
  margin: 0 0 0 500px;
  padding: 0;
}

.explanation .title{
  margin: 0;
  padding: 0;
  font-weight: bold;
  font-size: 18px;
}

.explanation .text {
  margin: 10px 0 0;
  padding: 0;
}

.sns-icon {
  padding-top: 15px;
  position: relative;
}
.x-icon {
  width: 9%; /*画像サイズ指定*/
  margin: 0;
  padding: 0;
}

.github-icon {
  width: 7%; /*画像サイズ指定*/
  margin: 0;
  padding: 0;
  margin-bottom: 10px;
  position: relative;
  left: 10px;
}

.discord-icon {
  width: 9%; /*画像サイズ指定*/
  margin: 0;
  padding: 0;
  position: relative;
  left: 30px;
}

.skill {
  height: 400px;
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
