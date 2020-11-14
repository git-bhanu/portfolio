<template>
  <div class="mx-12 my-12 ml-20">
    <img src="@/assets/images/bhanu.png" alt="">
    <h1 class="text-6xl antialiased leading-none mt-4">Bhanu <br>Singh</h1>
    <div class="mt-10">
      <Intropoint v-for="(point, index) in points" :key="index" :text='point'/>
    </div>
    <IntroSocial />


    <div>
      <p>Working <a href="https://agency.krenovate.com/" target="_blank" class="underline">@Krenovate</a></p>
      <p class="mb-4 text-gray-400">New Delhi, India</p>
      <a href="mailto: hey@bhanusingh.in"><p class="text-gray-400">hey@bhanusingh.in</p></a>
    </div>
  </div>
</template>


<script>

  export default {
    data () {
      return {
        points : ['Web Developer', 'WordPress, WooCommerce, Sage (roots.io), Laravel, VueJS']
      }
    }
  }
</script>
