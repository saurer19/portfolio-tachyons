<template>
  <div class="background-perfil vh-100 w-100 flex flex-column">
    <div class="h-100 f1 pa3 pa4-ns bg-white black-70 measure-narrow f3 times">
      <header class="bb b--black-70 pv4">
        <h3 class="f2 fw7 ttu tracked lh-title mt0 mb3 avenir">Gabriel Rivas</h3>
        <h4 class="f3 fw4 lh-title mt-0">Software Developer</h4>
      </header>
      <section
        class="pt5 pb4"
      >I am passionate about technology and truly enjoy the work in this field. My eagerness to learn and desire to gain experience have led me to engage in a wide variety of roles including mobile applications, websites, and back-end development.</section>
    </div>
    <nav>
      <div class="tc pb3 pa3">
        <a class="link dim gray f6 f5-ns dib mr3" href="#" title="Home">Home</a>
        <a class="link dim gray f6 f5-ns dib mr3" href="#" title="About">Skills</a>
        <a class="link dim gray f6 f5-ns dib mr3" href="#" title="Store">Experience</a>
        <a class="link dim gray f6 f5-ns dib mr3" href="#" title="Store">Education</a>
        <a class="link dim gray f6 f5-ns dib" href="#" title="Contact">Contact</a>
      </div>
    </nav>
  </div>
</template>

<script>
</script>

<style>
.background-perfil {
  background: url(/avila.jpg) no-repeat bottom fixed;
  background-size: cover;
}
nav {
  background-color: white;
}
@media screen and (min-width: 30em) {
  .pa4-ns {
    padding: 2rem;
  }
  .bg-white {
    background-color: rgba(255, 255, 255, 0.9);
  }
}
</style>
