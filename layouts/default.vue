<template>
  <div>
    <header>
      <h1>Ryoichi Portfolio</h1>
      <nav>
        <div class="nav-links">
          <nuxt-link to="/">Home</nuxt-link>
          <nuxt-link to="/project">Projects</nuxt-link>
          <nuxt-link to="/blog">Blog</nuxt-link>
          <nuxt-link to="/contact">Contact</nuxt-link>
        </div>
      </nav>
    </header>

    <main>
      <nuxt />
    </main>

    <footer>
      <p>&copy; 2023 Ryoichi Portfolio</p>
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
    padding:10px 30px;
    text-decoration: none;
    color: #333;
    position: relative;

  }

  header a:hover {
    color:#0481A2;
  }

  header a::after{
    content: '';
    position: absolute;
    bottom: 0;
    left: 10%;
    width: 80%;
    height: 2px;
    background:#0481A2;
    transition: all .3s;
    transform: scale(0, 1);
    transform-origin: center top;
  }

  header a:hover::after{
    transform: scale(1, 1);
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
