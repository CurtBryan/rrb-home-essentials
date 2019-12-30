<template>
  <header>
    <router-link to="/">
      <img
        src="https://riversiderockandboulder.com/wp-content/uploads/2018/07/RiversideRockandBoulderresized.png"
        alt="riverside logo"
      />
    </router-link>
    <div class="nav-link-wrapper">
      <router-link to="/">Home</router-link>
      <router-link to="/">Products</router-link>
      <router-link to="/contact">Contact</router-link>
    </div>
  </header>
</template>

<script>
export default {
  name: "navigation"
};
</script>

<style lang="scss" scoped>
header {
  width: 100%;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 30px 20px;
  img {
    height: 30px;
  }
}
.nav-link-wrapper {
  a {
    padding: 0 10px;
    font-size: 1.2rem;
    font-weight: 600;
    text-decoration: none;
    color: black;
    transition: all 0.2s ease-in-out;
    &:hover {
      color: #f89f7b;
    }
  }
}
</style>
