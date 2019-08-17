<template>
  <div class="h-100 f1 pa3 pa4-ns bg-white black-70 f3 times">
    <section class="mw7 mb5">
      <header class="bb b--black-70 pv4">
        <h3 class="f2 fw7 ttu tracked lh-title mt0 mb3 avenir">Experience</h3>
      </header>
      <article v-for="(job, i) in jobs" :key="i" class="pv4 bt bb b--black-10 ph3 ph0-1">
        <div class="flex flex-column flex-row-ns">
          <div class="w-100 w-60-ns pr3-ns order-2 order-1-ns">
            <h1 class="f3 mt0 lh-title">{{job.name}}</h1>
            <p class="f5 f4-l lh-copy">{{job.description}}</p>
          </div>
          <div class="pl3-ns order-1 order-2ns mb4 mb0-ns w-100">
            <img :src="job.img" class="db" />
          </div>
        </div>
      </article>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {
      jobs: [
        {
          name: "City Wallet",
          link:"https://www.citywallet.net",
          time: "Mar 2015 - Sep 2016",
          location: "Caracas, VE",
          position:"Software Developer",
          description:
            "My responsabilities are to research and develop in the area of NFC technology (Near Field Communication) to create an intelligent payment system and achieve its integration to existing platforms (ex. Parking lot equipment and public transportation).",
          img: "/citywallet.png"
        },
        {
          name: "PGA Group",
          link:"http://pgagroup.online/",
          time: "Apr 2017 - Jul 2017",
          location: "Caracas, VE",
          description:"I had the opportunity to focus on analyzing the customer needs and I was able to develop a web application which meets their requirements.",
          img: "/pga.jpg"
        },
        
      ]
    };
  }
};
</script>

<style>
@media screen and (min-width: 30em) {
  .pa4-ns {
    padding: 2rem;
  }
  .bg-white {
    background-color: rgba(255, 255, 255, 0.9);
  }
}
</style>
