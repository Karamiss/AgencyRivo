<template>  
        <!-- <h1>WE ARE RIVO AGENCY</h1>
      <section class="cover">
       
          
    <div class="Kfau">
      <div class="we-help">
        <img src="/src/assets/HomeView/preview_icon-1.png">
        <span>WE HELP</span>
      </div>
      <div class="ideas">
        <span>IDEAS</span>
        <img class="icon-click" src="/src/assets/HomeView/preview_icon-click.png">
      </div>
      <div>
        <img src="/src/assets/HomeView/preview_icon-2.png">
        <span>CHANGE</span>
      </div>
      <div>
  
        <span>THE WORLD</span>
      </div>
    </div>
  </section> -->

  <div class="grid head-description">
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
  
  <div class="">
  
    <div class="scroll_wrapper">
      <img src="/src/assets/HomeView/Scroll_to_explore.svg" alt="Scroll to explore">
    </div>
    
    <div>
      <img src="/src/assets/HomeView/сontact_us_button.svg" alt="=Contact us button"> 
    </div>
    
  </div>

  </template>
  
  <script setup>
 
  </script>
  
  <style scoped>


.grid {
  text-transform: uppercase;
  box-sizing: border-box;
  display: grid;
  grid-auto-flow: row;
  font-weight: 400;
}
.grid .head-description {
  line-height: 100%;  
}
.head-description>div {
  align-items: center;
  display: grid;
  gap: 20px;
  grid-auto-flow: column;
  font-size: 14vw;
}
.item-1, .item-2, .item-3, .item-4 {
  display: flex;
  justify-content: center;
}
img {
  object-fit: cover;
  height: 12vw;
}

.scroll_wrapper {
  display: flex;
  justify-content: center;
} 
</style>

  