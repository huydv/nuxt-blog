<template>
  <header class="header">
    <ul>
      <li class="nav-items">
        <nuxt-link to="/">Home</nuxt-link>
      </li>
      <li class="nav-items">
        <nuxt-link to="/users">Users</nuxt-link>
      </li>
    </ul>
  </header>
</template>
<script>
export default {

}
</script>
<style scoped>
  .header {
    widows: 100%;
    height: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .nav-items {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: space-around;
    align-items: center;
    widows: 80%;
  }

    .nav-items a {
      text-decoration: none;
    }
</style>
