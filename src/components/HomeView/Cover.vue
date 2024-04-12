<template>  
        <h1>WE ARE RIVO AGENCY</h1>
      <section class="cover">
        <!-- <div class="cover-title"> -->

        <!-- </div> -->
          
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
  </section>
  
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
  const data = {
    name: "about-us",
    data() {
      return {
        data: [
          {
            title: "Hi! We are a team of professionals",
            text: "With proven expertise in delivering effective, secured and high-quality digital solutions for various industries and digital marketing.",
          },
          {
            title: "Our company",
            text: "Offers development of different products starting from simple promo websites for individuals or companies, and finishing with complicated solutions for multiple purposes, e.g. <br><br>CRM and ERP systems, scalable web platforms, mobile applications, Internet-of-Things, etc.<br>We apply our expertise and knowledge to take your product from concept to prototype and to production.",
          }
        ]
      };
    }
  };
  </script>
  
  <style scoped>
  .icon-click {
    padding: 0 0px 0 20px;
    width: clamp(160px, 15vw, 373px);
  }
  img {
    padding: 0 20px 0 0;
      width: clamp(74px, 10vw, 168px);
  }
  span {
    color: #1A1A1A;
    font-size: clamp(60px, 15vw, 139px);
  }
  .Kfau {
    box-sizing: border-box;
    border: 1px dashed #e96004;
    white-space: nowrap;
  }
  .cover {
    display: flex;
    justify-content: center;
    width: 100%;
    /* padding: 20px; */
  }
  h1 {
    display: flex;
    justify-content: center;
    max-width: 100%;
    text-align: center;
    color: #818181;
    font-size: 20px;
  }
  .scroll_wrapper {
    display: flex;
    justify-content: center;
  }
  
  </style>
  
  