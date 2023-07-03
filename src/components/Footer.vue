<script setup>

</script>

<template>
  <footer class="footer">
    <svg width="1440" height="36" viewBox="0 0 1440 36" class="u-block" xmlns="http://www.w3.org/2000/svg"
         style="width: 100%; height: auto;">
      <rect width="100%" height="100%" fill="#F6F6F7"></rect>
      <path
          d="M1440 36V8.2s-105.6-1.2-160.7-6a877 877 0 00-150.5 2.5c-42.1 3.9-140 15-223 15C754 19.6 700.3 6.8 548.8 7c-143.7 0-273.4 11.5-350 12.6-76.6 1.2-198.8 0-198.8 0V36h1440z"
          fill="#FFD000"></path>
    </svg>
    <div>

    </div>
  </footer>
</template>

<style scoped lang="scss">
@import "@/styles/variables";

.footer {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

div {
  width: 100%;
  background: #FFD000;
  height: 140px;

  @include tablet(){
    height: 258px;
  }
}

</style>