<template>
  <div class="bg-white-80 black-70 h-100 times pa3 pa4-ns ">
    <section class="fl w-100 w-50-ns tc">
      <Header title="education"></Header>
    </section>
    <section class="fl w-100 w-50-ns tc">
            <Header title="skills"></Header>

    </section>
  </div>
</template>

<script>
import  Header  from "../components/Header";
export default {
  components:{
    Header
  },  
};
</script>

<style>
@media screen and (min-width: 30em) {
  .pa4-ns {
    padding: 2rem;
  }
}
</style>
