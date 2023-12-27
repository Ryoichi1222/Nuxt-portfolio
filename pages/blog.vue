<template>
    <div>
      <h2>My Blog</h2>
      <ul>
        <li>
          <h3>Blog Post 1</h3>
          <p>This is the content of my first blog post.</p>
        </li>
        <li>
          <h3>Blog Post 2</h3>
          <p>This is the content of my second blog post.</p>
        </li>
        <!-- Add more blog posts as needed -->
      </ul>
      <nuxt-link to="/">Back to Home</nuxt-link>
      <nuxt-link to="/projects">View Projects</nuxt-link>
      <nuxt-link to="/contact">Contact Me</nuxt-link>
    </div>
  </template>
  
  <script>
  export default {
    name: 'Blog',
  }
  </script>
  
  <style scoped>
  /* Add your styles here */
  </style>
  