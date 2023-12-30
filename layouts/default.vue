<template>
  <div>
    <header>
      <h1>Ryoichi Portfolio</h1>
      <nav>
        <div class="nav-links">
          <nuxt-link to="/">Home</nuxt-link>
          <nuxt-link to="/projects">Projects</nuxt-link>
          <nuxt-link to="/blog">Blog</nuxt-link>
          <nuxt-link to="/contact">Contact</nuxt-link>
        </div>
      </nav>
    </header>

    <main>
      <nuxt />
    </main>

    <footer>
      <p>&copy; 2023 My Portfolio</p>
    </footer>
  </div>
</template>

<style>
/* Add your global styles here */
body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background-color: #cefff4;
  color: #080808;
  padding: 50px;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

header a {
    text-decoration: none; /* 下線を非表示にする */
    color: #333; /* リンクの色を指定 */
    margin-right: 40px; /* リンク間の余白を調整 */
    line-height: 40px;
  }

  header a:hover {
    background-color: #fff;
    letter-spacing: 0.15em;
  }



main {
  padding: 1rem;
}

footer {
  background-color: #333;
  color: #fff;
  padding: 1rem;
  text-align: center;
}
</style>
