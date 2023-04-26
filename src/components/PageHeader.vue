<script>
import infos from './data/nexgen_header.json';
import InfoBar from './InfoBar.vue'
export default{
    name: 'PageHeader',
    components: {
        InfoBar
    },
    data(){
        return{
            infos: infos
        }
    }
}

</script>

<template>
    <header>

                                        <!-- TOP HEADER -->

        <div class="top_header">
            <div class="container">
                <div class="row pt-3">
                    <div class="col">
                        <InfoBar :open_hours="info.open_hours" :cell_number="info.cell_number" :email="info.email" v-for="info in infos"></InfoBar>
                    
                </div>
            </div>
        </div>
        </div>

                                <!-- /TOP HEADER -->

                                <!-- BOTTOM HEADER -->


        <div class="bottom_header">
            <div class="jumbotron">
                <div class="container">
                    <div class="row">

                                                            <!-- NAVBAR -->


                        <nav class="navbar navbar-expand-lg bg-body-tertiary justify-content-between text_size mt-5">
                        
                            <a class="navbar-brand text-light logo_scss" href="#"><span class="text_primary logo_scss_span">NEX</span>GEN</a>
                            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavAltMarkup" aria-controls="navbarNavAltMarkup" aria-expanded="false" aria-label="Toggle navigation">
                              <span class="navbar-toggler-icon"></span>
                            </button>
                            <div class="" id="navbarNavAltMarkup">
                              <div class="navbar-nav gap-5">
                                <a class="nav-link active text-light" aria-current="page" href="#">HOME</a>
                                <a class="nav-link text-light" href="#">ABOUT</a>
                                <a class="nav-link text-light" href="#">SERVICE</a>
                                <a class="nav-link text-light">PROCESS</a>
                                <a class="nav-link text-light">TESTIMONIALS</a>
                                <a class="nav-link text-light"><svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-person-fill" viewBox="0 0 16 16">
                                <path d="M3 14s-1 0-1-1 1-4 6-4 6 3 6 4-1 1-1 1H3Zm5-6a3 3 0 1 0 0-6 3 3 0 0 0 0 6Z"/>
                                </svg></a>
                                <button class="btn  bg_primary text-light text_size">GET IN TOUCH</button>
                              </div>
                            </div>
                        
                        </nav>

                                                                    <!-- /NAVBAR -->

                                                                    <!-- JUMBO PRESENTATION -->

                        
                        <div class="col-8 text-light ">
                            <h6 class="text_primary">LOGISTIC SERVICE</h6>
                            <h1>CARGO TRANSPORT</h1>
                            <p id="presentation_p">Fractional or exclusive road cargo transportation to all regions, with small, medium and large vehicles.</p>
                            <div class="btn_container d-flex gap-4 mt-4 ps-2">
                                <button class="btn text-light bg_primary">GET IN TOUCH</button>
                                <button class="btn btn_border text-light">READ MORE</button>
                            </div>
                        </div>                                                





                                                                    <!-- /JUMBO PRESENTATION -->


                    </div>
                </div>
            </div>                            
        </div>     

                                <!-- /BOTTOM HEADER -->

    </header>
 
</template>

<style lang="scss" scoped>
@use './scss/partials/variables.scss' as *;

.top_header{
    background-color: $bg-secondary;
    color: $text-dark;
}
.bottom_header{
    background-image: url('/img/bg-9.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    height: 850px;

    .jumbotron{
        background-color:$bg-dark;
        height: 100%;

        .text_size{
            font-size: 1.2rem;
            font-weight: 600;
        }
        #presentation_p{
            color: $text-dark;
        }
   
    }

    .logo_scss{
        font-size: 2rem;
        font-weight: 700;
    }

    .logo_scss_span{
        border-top-left-radius: 40px;
        border-bottom-left-radius: 40px;
        background-color: $primary-transparent;
        padding: 3px;
        padding-left: 35px;
        padding-right: 5px;
        margin-right: 5px;
    }
    .text_primary{
        color: $primary;
    }

    .bg_primary{
        background-color: $primary;
    }
    .btn_border{
        border-color: $primary;
    }
   
    .col-8{
        
        margin-top: 100px;

        h6{
            font-size: 1.3rem;
        }
        h1{
            font-size: 5.8rem;
            font-weight: 700;
        }
        p{
            font-size: 1.3rem;
            padding-left: 15px;
        }
        button{
            border-radius: 0;
            border-radius: 3px;
            font-weight: 600;
            font-size: 1.2rem;
        }
    }
}

</style>