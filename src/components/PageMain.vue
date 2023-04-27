<script>
export default{
    name: 'PageMain'
}

</script>

<template>
  <div class="container">
    <div class="row">
        <div class="col-8 d-flex flex-column">
            <h6 class="text_primary mt-5">WHO WE ARE</h6>
            <h2 class=" mt-3">
                <span class=" me-3">
                    <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" fill="currentColor" class="bi bi-gem" viewBox="0 0 16 16">
                      <path d="M3.1.7a.5.5 0 0 1 .4-.2h9a.5.5 0 0 1 .4.2l2.976 3.974c.149.185.156.45.01.644L8.4 15.3a.5.5 0 0 1-.8 0L.1 5.3a.5.5 0 0 1 0-.6l3-4zm11.386 3.785-1.806-2.41-.776 2.413 2.582-.003zm-3.633.004.961-2.989H4.186l.963 2.995 5.704-.006zM5.47 5.495 8 13.366l2.532-7.876-5.062.005zm-1.371-.999-.78-2.422-1.818 2.425 2.598-.003zM1.499 5.5l5.113 6.817-2.192-6.82L1.5 5.5zm7.889 6.817 5.123-6.83-2.928.002-2.195 6.828z"/>
                    </svg>
                    Excellence 
                </span>
                in Transport
            </h2>
            <p class="mt-3">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Sequi, doloremque voluptas! Iusto soluta voluptatibus nulla enim et! Aliquam, blanditiis architecto?</p>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Vel possimus voluptatibus cum at veritatis iste.</p>
            <p class="p_left_border pt-4">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Velit veniam minus dolore magnam expedita animi.</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Obcaecati, asperiores?</p>
            <ul>
                <li>Lorem, ipsum dolor.</li>
                <li>Lorem, ipsum dolor.</li>
                <li>Lorem ipsum dolor sit.</li>
                <li>Lorem, ipsum.</li>
                <li>lorem</li>
            </ul>
        </div>

        <div class="col-4 d-flex flex-column gap-2 mb-5">
            <h3 class="mt-5 mb-4">Vehicle Types</h3>
            <div class="vehicle d-flex">
                <div class="img_container">
                    <img src="/img/truck-1.png" alt="">
                </div>
                <div class="text_container">
                    <h2><strong>Light</strong></h2>
                    <p>Max Weight  1200kg</p>
                </div>
            </div>

            <div class="vehicle d-flex">
                <div class="img_container">
                    <img src="/img/truck-1.png" alt="">
                </div>
                <div class="text_container">
                    <h2><strong>Medium</strong></h2>
                    <p>Max Weight  6000kg</p>
                </div>
            </div>

            <div class="vehicle d-flex">
                <div class="img_container">
                    <img src="/img/truck-1.png" alt="">
                </div>
                <div class="text_container">
                    <h2><strong>Heavy</strong></h2>
                    <p>Max Weight  24000kg</p>
                </div>
            </div>
        

            <div class="certifications">
                <h3 class="mb-4 mt-2">Certifications</h3>
                <img src="/img/certificate.png" alt="">
                <img src="/img/certificate.png" alt="">
            </div>
        </div>

    </div>
  </div>
</template>

<style lang="scss" scoped>
@use './scss/partials/variables.scss' as *;

.col-8{
    span{
        background-color: $primary;
        color: $bg-secondary;
        font-size: 3rem;
        font-weight: 700;
        padding-left: 10px;
        padding-bottom: 4px;
    }
    h2{
        font-size: 3rem;
        font-weight: 700;
    }

    h6{
        font-weight: 700;
    }
}
.vehicle{
    img{
        height: 70px;
        margin: 0.4rem;
    }
}

.certifications img{
    height: 100px;
}

.text_primary{
        color: $primary;
 }

.p_left_border{
    border-left: 5px solid $primary;
    height: 80px;
    text-align: center;
    font-style: italic;
}
.img_container{
    background-color: $secondary;
    border-radius: 10px;
}
  
</style>