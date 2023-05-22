<template>
  <div>
    <b-nav class="navbar-menu-items" tabs>
      <!-- Use BEM class here -->
      <b-nav-item class="item" header="Home">Home</b-nav-item>
      <b-nav-item class="item" header="Songs&Eps">Songs&Eps</b-nav-item>
      <b-nav-item class="item" header="Store">Store</b-nav-item>
      <b-nav-item class="item" header="About">About</b-nav-item>
      <b-nav-item class="item" header="Blog">Blog</b-nav-item>
    </b-nav>
  </div>
</template>

<style lang="scss">
.navbar-menu-items {
  font-size: 20px;
}

.item {
  padding: 10px;
  color: white;
}
.nav-link {
  color: white;
}
</style>
