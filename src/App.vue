<template>
  <div id="app">
    <div class="db-cont">
      <div id="nav">
        <Navigation />
      </div>
      <router-view />
    </div>
  </div>
</template>

<script>
/* colors: 
green: #90957A
tan: #F89F7B
*/

import Navigation from "./components/Navigation";
export default {
  name: "app",
  components: {
    Navigation
  }
};
</script>

<style lang="scss">
#app {
  font-family: "Roboto", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  width: 100vw;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.db-cont {
  width: 100%;
  max-width: 1200px;
}
html {
  box-sizing: border-box;
  font-size: 16px;
}

*,
*:before,
*:after {
  box-sizing: inherit;
}

body,
h1,
h2,
h3,
h4,
h5,
h6,
p,
ol,
ul {
  margin: 0;
  padding: 0;
  font-weight: normal;
}

ol,
ul {
  list-style: none;
}

img {
  max-width: 100%;
  height: auto;
}
</style>
