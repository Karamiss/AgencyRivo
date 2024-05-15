<template>
    <section id="industry">
        <div class="container">
            <h2 class="font-2-h1">Industries</h2>
            <div class="industries-inner grid cols-lg-2 block-hover-show-image">
                <div class="left">
                    <a href="https://rivo.agency/expertises/retail-and-e-commerce-software-development/" data-index="image_0" class="industry-row item font-1-h3">
                        <h3 class="title">Retail &amp; Ecommerce </h3>
                        <span class="arrow" data-rocket-lazy-bg="loaded"></span>
                    </a>
                    <a href="https://rivo.agency/expertises/real-estate-software-development/" data-index="image_1" class="industry-row item font-1-h3">
                        <h3 class="title">Real Estate</h3>
                        <span class="arrow" data-rocket-lazy-bg="loaded"></span>
                    </a>
                    <a href="https://rivo.agency/expertises/custom-crm-software-development/" data-index="image_2" class="industry-row item font-1-h3">
                        <h3 class="title">Custom CRM</h3>
                        <span class="arrow" data-rocket-lazy-bg="loaded"></span>
                    </a>
                    <a href="https://rivo.agency/expertises/custom-e-learning-software-development/" data-index="image_3" class="industry-row item font-1-h3">
                        <h3 class="title">Education &amp; e-learning</h3>
                        <span class="arrow" data-rocket-lazy-bg="loaded"></span>
                    </a>
                    <a href="https://rivo.agency/expertises/restaurant-management-software/" data-index="image_4" class="industry-row item font-1-h3">
                        <h3 class="title">Food &amp; Restaurant</h3>
                        <span class="arrow" data-rocket-lazy-bg="loaded"></span>
                    </a>
                    <a href="https://rivo.agency/expertises/healthcare-app-development-company/" data-index="image_5" class="industry-row item font-1-h3">
                        <h3 class="title">Healthcare &amp; Fitness</h3>
                        <span class="arrow" data-rocket-lazy-bg="loaded"></span>
                    </a>
                    <a href="https://rivo.agency/expertises/logistics-software-development/" data-index="image_6" class="industry-row item font-1-h3">
                        <h3 class="title">Logistics &amp; Distribution</h3>
                        <span class="arrow" data-rocket-lazy-bg="loaded"></span>
                    </a>
                </div>

                <div class="right">
                    <img data-index="image_0" src="https://rivo.agency/wp-content/uploads/2023/08/retail_e_commerce.webp" alt="" class="visible">
                    <img data-index="image_1" src="https://rivo.agency/wp-content/uploads/2023/08/real_estate.webp" alt="" class="visible">
                    <img data-index="image_2" src="https://rivo.agency/wp-content/uploads/2023/08/custom_crm.webp" alt="" class="">
                    <img data-index="image_3" src="https://rivo.agency/wp-content/uploads/2023/08/education_e_learning.webp" alt="" class="">
                    <img data-index="image_4" src="https://rivo.agency/wp-content/uploads/2023/08/food_restaurant.webp" alt="" class="">
                    <img data-index="image_5" src="https://rivo.agency/wp-content/uploads/2023/08/healthcare_fitness.webp" alt="" class="">
                    <img data-index="image_6" src="https://rivo.agency/wp-content/uploads/2023/12/service-logistics.webp" alt="" class="">
                </div>
            </div>
        </div>
    </section>
</template>


<style scoped>
section {
    padding-top: 72px;
    padding-bottom: 72px;
}

section {
    display: grid;
    width: 100%;
}

.grid {
    gap: 20px;
    grid-auto-flow: row;
}
h2+* {
    margin-top: 52px;
}

.grid {
    box-sizing: border-box;
    display: grid;
}

.industry-row {
    -webkit-box-align: center;
    -ms-flex-align: center;
    -webkit-box-pack: justify;
    -ms-flex-pack: justify;
    align-items: center;
    border-bottom: 1px solid #d8d7db;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    justify-content: space-between;
    padding: 22px 0;
    position: relative;
}

.industry-row .arrow, .industry-row h3 {
    -webkit-transition: all .3s;
    transition: all .3s;
}
.industry-row h3 {
    padding-left: 0;
}

.industry-row .arrow {
    -ms-flex-negative: 0;
    background-color: #fff;
    border-radius: 50%;
    display: inline-block;
    flex-shrink: 0;
    height: 32px;
    margin-left: 10px;
    position: relative;
    width: 32px;
}

.industry-row {
    -webkit-box-align: center;
    -ms-flex-align: center;
    -webkit-box-pack: justify;
    -ms-flex-pack: justify;
    align-items: center;
    border-bottom: 1px solid #d8d7db;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    justify-content: space-between;
    padding: 22px 0;
    position: relative;
}

.industry-row .arrow:after {
    background-image: var(--wpr-bg-a2cc1f8e-5e2a-434a-9861-c1a52fa4b7ce);
    background-position: 50%;
    background-repeat: no-repeat;
    background-size: contain;
    content: "";
    height: 11px;
    left: 50%;
    position: absolute;
    top: 50%;
    -webkit-transform: translate(-50%,-50%);
    transform: translate(-50%,-50%);
    -webkit-transition: all .3s;
    transition: all .3s;
    width: 11px
}

@media screen and (min-width: 768px) {
    #cover .figure {
        display:block;
        position: absolute;
        z-index: -1
    }

    #cover .figure.left {
        bottom: -100px;
        left: 0;
        -webkit-transform: translateX(-50%) rotate(-6.5deg);
        transform: translateX(-50%) rotate(-6.5deg)
    }

    #cover .figure.right {
        right: 0;
        top: 100px;
        -webkit-transform: translateX(50%) rotate(13.85deg);
        transform: translateX(50%) rotate(13.85deg)
    }
}

@media (max-width: 992px) {
#industry .right {
    display: none;
}
}
#industry .right {
    position: relative;
}

.industry-row:hover .arrow {
    background-color: #000
}

.industry-row:hover .arrow:after {
    -webkit-filter: invert(1);
    filter: invert(1)
}

#industry .right img {
    height: 100%;
    left: 0;
    -o-object-fit: cover;
    object-fit: cover;
    opacity: 0;
    position: absolute;
    top: 0;
    -webkit-transition: opacity .3s;
    transition: opacity .3s;
    width: 100%;
}
img {
    max-width: 100%;
}

img {
    overflow-clip-margin: content-box;
    overflow: clip;
}

a {
    color: inherit;
    text-decoration: none;
}
</style>

