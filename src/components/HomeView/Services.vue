<template>
  <div class="service-wrapper">
    <div class="service-details">
      <div>
        <div class="large-text">Custom</div>
        <div class="large-text">Software</div>
      </div>
        <div class="service">
          Using our great experience in a variety of technology stacks and industries,
          we provide customized software tailored to your business needs. Our experts 
          design and develop a fast-loading, secure, and scalable SaaS solution that 
          easily integrates with third-party services.
        </div>
        <div class="service-card">
          <!-- <img class="test-img " src="/images/services_customSoftware.png"> -->
        </div>
    </div>
  </div>

  <div class="service-wrapper">
    <div class="service-details">
      <div>
        <div class="large-text">Mobile</div>
        <div class="large-text">Development</div>
      </div>
        <div class="service">
          Request mobile app development at Rivo Agency to present your business to 
          a wider audience, keep in touch with your customers, discover their needs 
          and win their loyalty. Our app developers create customized solutions for 
          iOS and Android devices that simplify customer interactions.
        </div>
        <div class="service-card">
          <!-- <img src="/images/services_mobileDevelopment.png"> -->
        </div>    
    </div>
  </div>

  <div class="service-wrapper">
    <div class="service-details">
      <div>
        <div class="large-text">Web</div>
        <div class="large-text">Development</div>
      </div>
        <div class="service">
          Start developing your software with us to improve the efficiency of your 
          business and attract potential customers. Having 10+ years of experience 
          as a web and mobile app development company, we know how to create fast 
          and powerful web apps that will serve your business for years.
        </div>
        <div class="service-card">
          <!-- <img src="/images/services_webDevelopment.png"> -->
        </div>
      </div>
  </div>
</template>

<script>
// export default {
//   name: "main-services",
  
// };
</script>

<style scoped>



.test-img {
	display: flex;
	align-items: center;
	justify-content: center;
	width: 300px;
}
.service-details {
	display: flex;
	position: relative;
	flex: 1;
  align-items: center;
	justify-content: space-between;
	overflow: hidden;
}

.service {
	transition: 0.4s;
	margin: 0px 0px 105px 0px;
	padding-right: 200px;
	width: 50%;

	margin: 24px 0px;
	line-height: 150%;
	color: #818181;
	/* font-family: Gilroy; */
	font-size: 17px;
	font-weight: 500;
}
.service-card {
	position: absolute;
	/* top: 53px; */
	right: -190px;
	transition: 0.4s;
	/* width: 200px; */
  width: 337px;
	/* height: 50px; */

}
.service-details:hover .service {
	transform: translateX(-100px);
}
.service-details:hover .service-card {
	transform: translateX(-300px);
}
.service-wrapper {
	display: flex;
}
.service-details div {
	flex: 1;
	max-width: clamp(188px, 2vw, 700px);
}
.large-text {
	margin-right: 20px;
	font-size: clamp(24px, 2vw, 52px);
	font-weight: 600;
}


</style>
