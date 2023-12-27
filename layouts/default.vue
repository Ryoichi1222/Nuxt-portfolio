<template>
  <div>
    <header>
      <h1>My Portfolio</h1>
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
  background-color: #333;
  color: #fff;
  padding: 1rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav {
  display: flex;
}

.nav-links {
  display: flex;
}

nav nuxt-link {
  margin-right: 10rem;
  color: rgb(240, 237, 237);
  text-decoration: none;
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
