<template>
  <footer>
    <p>Copyright &copy; 2021</p>
    <router-link to="/about">About</router-link> <!-- this is to not refresh the page but load the page without refreshing -->
  </footer>
</template>

<style scoped>
a {
  color: #333;
}

footer {
  margin-top: 30px;
  text-align: center;
}
</style>