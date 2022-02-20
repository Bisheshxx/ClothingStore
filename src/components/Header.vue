<template>
  <header>
    <div class="header__navigation">
      <div class="header__navigation_pages">
        <span>Home</span>
        <span>Men</span>
        <span>Women</span>
        <span>Kids</span>
      </div>
      <div class="header__navigation_pages">
        <span>Login</span>
        <span>Cart</span>
      </div>

    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style scoped>
.header__navigation {
  display: flex;
  justify-content: space-between;
}
.header__navigation_pages{
    display: flex;
  justify-content: space-evenly;
  width: 400px;
  float: left;
}
</style>