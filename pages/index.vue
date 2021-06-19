<template>
  <div>
    <div class="first-page bg-gray-800 text-white h-screen flex flex-col justify-between">
      <div class="content flex flex-col-reverse sm:flex-row md:flex-row w-full items-center h-2/6 md:h-5/6 sm:h-5/6">
        <div class="date flex items-center">
          <div class="text flex sm:flex-col md:flex-col px-4 text-center text-xl">
            <p>01</p> 
            <p>/</p>
            <p>02</p>
          </div>
        </div>
        <div class="header flex justify-center w-full">
          <p class="text-3xl sm:text-4xl md:text-8xl tracking-widest">
            KADINGEH
          </p>
        </div>
      </div>
      <nuxt-link to="/explore" class="button flex h-1/6 justify-end">
        <div class="text-white py-4 text-2xl tracking-widest font-semibold  bg-gray-500 w-full md:w-1/5 sm:w-1/5 flex justify-center items-center">
          Show More
        </div>
      </nuxt-link>
    </div>
  </div>
</template>

<script>
  export default {
    transition: 'slide-bottom'
  }
</script>

<style>
  .first-page {
    background-image: url('../assets/img/photo6217556209045712351.jpg');
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  }
</style>
