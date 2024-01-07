<template>
  <div>
    <h1>Contact us  </h1>
    <form action="https://ryoichi.form.newt.so/v1/7DDu99Gwd" method="post">
      <label for="name">Name</label>
      <input id="name" name="name">
      <label for="email">Email</label>
      <input id="email" name="email" type="email">
      <label for="message">Message</label>
      <textarea id="message" name="message" />
      <button type="submit">
        Submit
      </button>
    </form>
  </div>
</template>
    
  
  <script>
  export default {
    name: 'Contact',
    meta: [{ name: 'description', content: 'NewtとNuxtを利用した問い合わせフォームです' }]
  }
  </script>
  
  <style scoped>
  div {
    margin-bottom: 500px;
  }  

  </style>
  