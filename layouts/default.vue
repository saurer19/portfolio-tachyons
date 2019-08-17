<template>
  <div class="background-perfil vh-100 w-100 flex flex-column">
    <nuxt />
    <nav class="shadow-1 tc pb3 pa3 fixed bg-white w-100 bottom-0">
        <nuxt-link class="link dim gray b f6 f5-ns dib mr3" to="/" exact>Home</nuxt-link>
        <nuxt-link class="link dim gray b f6 f5-ns dib mr3" to="/experience">Experience</nuxt-link>
        <nuxt-link class="link dim gray b f6 f5-ns dib mr3" to="/skills">Education & Skills</nuxt-link>
        <nuxt-link class="link dim gray b f6 f5-ns dib" to="/contact">Contact</nuxt-link>
    </nav>
  </div>
</template>

<style>
html {
  font-family: "Source Sans Pro", -apple-system, BlinkMacSystemFont, "Segoe UI",
    Roboto, "Helvetica Neue", Arial, sans-serif;
  font-size: 16px;
  word-spacing: 1px;
  -ms-text-size-adjust: 100%;
  -webkit-text-size-adjust: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
*,
*:before,
*:after {
  box-sizing: border-box;
  margin: 0;
}

.background-perfil {
  background: url(/avila.jpg) no-repeat bottom fixed;
  background-size: cover;
}
.nuxt-link-active {
  font-weight: bold;
  border-bottom: solid 2px;
}
</style>
