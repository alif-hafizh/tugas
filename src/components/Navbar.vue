<template>
  <header class="navbar">

    <h2>SMK YADIKA SOREANG - Onlineshop</h2>

    <nav>
      <RouterLink to="/">Landing</RouterLink>
      <RouterLink to="/product">Product</RouterLink>
      <RouterLink to="/about">About</RouterLink>
      <RouterLink to="/contact">Contact</RouterLink>
    </nav>

  </header>
</template>

<style scoped>

.navbar {
  max-width: 1100px;
  height: 75px;
  margin: auto;
  padding: 0 25px;

  display: flex;
  align-items: center;
  justify-content: space-between;

  background: white;
}

.navbar h2 {
  margin: 0;
  color: #294a91;
  font-size: 20px;
}

nav {
  display: flex;
  gap: 25px;
}

nav a {
  color: #333;
  text-decoration: none;
}

nav a:hover {
  color: #405de6;
}

nav a.router-link-active {
  color: #405de6;
  font-weight: bold;
}

</style>