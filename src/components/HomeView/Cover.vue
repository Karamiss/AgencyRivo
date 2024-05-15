<template>  
<section id="cover">
  <div class=" cover-title">
  <img class="figure left" src="https://rivo.agency/wp-content/themes/rivo-agency/assets/src/images/big-waves.svg" alt="figure">

    <div class="grid head-description">
      <h1 class="font-2-h5">We are Rivo Agency</h1>
      <div class="item-1">
          <img class="cover-image-1" src="/src/assets/HomeView/preview_icon-1.png">
          We help
      </div>
      <div class="item-2">
          Ideas
          <img src="/src/assets/HomeView/preview_icon-click.png">
      </div>
      <div class="item-3">
          <img src="/src/assets/HomeView/preview_icon-2.png">
          Change
      </div>
      <div class="item-4">
          The world
      </div>
  </div>
  </div>

  <a class="scroll scroll_wrapper" href="">
    <img src="/src/assets/HomeView/Scroll_to_explore.svg" alt="Scroll to explore">
  </a>

  <!-- <img class="figure left" src="https://rivo.agency/wp-content/themes/rivo-agency/assets/src/images/big-waves.svg" alt="figure"> -->
  <!-- <img class="figure right" src="https://rivo.agency/wp-content/themes/rivo-agency/assets/src/images/big-waves.svg" alt="figure"> -->
</section>
<!-- <div class="">
    <div>
      <img src="/src/assets/HomeView/сontact_us_button.svg" alt="=Contact us button"> 
    </div>
  </div> -->
  </template>
  
  <script setup>
 
  </script>
  
<style lang="scss" scoped>
.figure.left {
  /* bottom: -100px;
  left: 0;
  transform: translateX(-50%) rotate(-6.5deg);
  max-width: 100%; */
}
.figure.right {
  /* right: 0;
  top: 100px;
  transform: translateX(50%) rotate(13.85deg); */
}
.figure {
  display: block;
  position: absolute;
  z-index: -1;
  & .left {
     right: 0;
  top: 100px;
  transform: translateX(50%) rotate(13.85deg); 
  }
}
.grid {
  text-transform: uppercase;
  box-sizing: border-box;
  display: grid;
  grid-auto-flow: row;
  font-weight: 400;
  /* border: thin solid black; */
  
}
.grid .head-description {
  line-height: 100%;  
}
.head-description>div {
  align-items: center;
  
  display: grid;
  gap: 20px;
  grid-auto-flow: column;
  /* font-size: 14vw; */
  font-size: 6.5vw;
}
.item-1, .item-2, .item-3, .item-4 {
  display: flex;
  justify-content: center;
}
img {
  object-fit: cover;
  height: 8vw;
}
.font-2-h5 {
  display: flex;
  font-weight: 400;
  font-size: 20px;
  justify-content: center;
  color: #5b5b5c;
  text-transform: uppercase;

}
.scroll_wrapper {
  display: flex;
  justify-content: center;
} 
</style>

  