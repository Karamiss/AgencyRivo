<template>
  <section class="about-us">
    <div class="container">
    <span class="">WHO WE ARE</span>
    <div class="about-wrapper">
      <div>
        <img class="test-img" src="/src/assets/HomeView/who-we-are-poster.png"/>
      </div>
      <div class="section-wrapper">
        <div v-for="(text, index) in data" :key="index">
          <div class="style">{{ text.title }}</div>
          <div class="small-text" v-html="text.text"></div>
        </div>
        <div class="clutch">
          <a href="https://clutch.co/profile/rivo-agency" rel="nofollow">
            <img src="/src/assets/HomeView/Cluch-rating.svg" alt="Clutch">
          </a>
        </div>
      </div>
    </div>
  </div>
</section>



</template>



<script>
export default {
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

@media (max-width: 1440px) {
.container {
    padding-left: 30px;
    padding-right: 30px;
}
}
.container {
  padding-left: 30px;
    padding-right: 30px;
}

.test-img {
  max-width: 100%;
}
.about-us {
	background: #eeeef0;
  width: 100%;
  padding-bottom: 72px;
  padding-top: 72px;
  /* margin: 0; */
}
.about-wrapper {
	display: flex;
	flex: 1;
	gap: 28px;
}
span {
	display: flex;
	justify-content: left;
	line-height: normal;
	white-space: nowrap;
	font-size: 52px;
	font-weight: 700;
	font-style: normal;
  margin-bottom: 20px;
}
.style {
	text-transform: uppercase;
	line-height: 100%;
	font-size: 24px;
	font-weight: 700;
	font-style: normal;
}
.small-text {
	margin: 24px 0px;
	line-height: 150%;
	color: #818181;
	font-family: Gilroy;
	font-size: 17px;
	font-weight: 500;
	font-style: normal;
}
</style>
