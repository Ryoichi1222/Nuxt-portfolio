<template>
  <div>
    <header>
      <h1>My Portfolio</h1>
      <nav>
        <nuxt-link to="/">Home</nuxt-link>
        <nuxt-link to="/projects">Projects</nuxt-link>
        <nuxt-link to="/contact">Contact</nuxt-link>
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
}

nav {
  display: flex;
}

nav nuxt-link {
  margin-right: 1rem;
  color: #fff;
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
