<template>
  <div class="overflow-hidden">
    <Nuxt />
  </div>
</template>

<style>
  .page-enter-active,
  .page-leave-active {
    transition: opacity 0.5s;
  }
  .page-enter,
  .page-leave-to {
    opacity: 0;
  }

  .layout-enter-active,
  .layout-leave-active {
    transition: opacity 0.5s;
  }
  .layout-enter,
  .layout-leave-to {
    opacity: 0;
  }

  .slide-bottom-enter-active,
  .slide-bottom-leave-active {
    transition: opacity 0.5s ease-in-out, transform 0.5s ease-in-out;
  }
  .slide-bottom-enter,
  .slide-bottom-leave-to {
    opacity: 0;
    transform: translate(0, 10px);
  }
  .bounce-enter-active {
    transform-origin: top;
    animation: bounce-in 0.8s;
  }
  .bounce-leave-active {
    transform-origin: top;
    animation: bounce-out 0.5s;
  }
  @keyframes bounce-in {
    0% {
      transform: scale(0);
    }
    50% {
      transform: scale(1.25);
    }
    100% {
      transform: scale(1);
    }
  }
  @keyframes bounce-out {
    0% {
      transform: scale(1);
    }
    50% {
      transform: scale(1.25);
    }
    100% {
      transform: scale(0);
    }
  }
</style>
