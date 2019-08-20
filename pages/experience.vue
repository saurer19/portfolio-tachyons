<template>
  <div class="  pa3 pa4-ns bg-white-80 black-70 f3 times">
    <section >
      <header class="bb b--black-70 pv4">
        <Header title="experience"></Header>
      </header>
      <article v-for="(job, i) in jobs" :key="i" class="pv4 bt bb b--black-10 ph3 ph0-1">
        <div class="flex flex-column flex-row-ns">
          <div class="w-100  pr3-ns order-2 order-1-ns">
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
import  Header  from "../components/Header";
export default {
  components:{
    Header
  },
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
          img: "/.png"
        },
        {
          name: "PGA Group",
          link:"http://pgagroup.online/",
          time: "Apr 2017 - Jul 2017",
          position:"Web Developer",
          location: "Caracas, VE",
          description:"I had the opportunity to focus on analyzing the customer needs and I was able to develop a web application which meets their requirements.",
          img: "/pga.jpg"
        },
        {
          name: "Firefly Integrations",
          link:"http://www.fireflyint.com/",
          time: "Oct 2018 - Present",
          position:"Web Developer",
          location: "Indiana, USA",
          description:"Firefly Integrations provides advanced automation and mobile electrical solutions for the RV and marine vehicle industries.",
          img: "/pga.jpg"
        },
        
      ]
    };
  }
};
</script>

<style>

</style>
