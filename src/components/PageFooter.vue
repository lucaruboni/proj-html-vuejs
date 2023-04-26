<script>
import infos from './data/nexgen_header.json';
export default{
    name: 'PageFooter',
    props:{
        open_hours: String,
        cell_number: String,
        email: String,
        address: String,
        about: Array,
        transport: Array,
        support: Array
    },
    data(){
        return{
            infos: infos
        }
    }
}

</script>

<template>
    <footer>
        <div class="top_footer">
            <div class="container">
                <div class="row row-cols-5 py-5 justify-content-evenly">
                    <div class="col name">
                        <a class="navbar-brand text-light logo_scss" href="#"><span class="text_primary logo_scss_span">NEX</span>GEN</a>
                        <p class="mt-4">A functional HTML Template for Corporate and Business</p>
                        <ul class="p-0 mt-4 d-flex gap-3 flex-column" >
                            <li>
                                <h6>{{ cell_number }}</h6>
                            </li>
                            <li>
                                <h6>{{ email }}</h6>
                            </li>
                            <li>
                                <h6>{{ address }}</h6>
                            </li>
                        </ul>

                        <button class="btn mt-4 btn_border text-light text_size">GET IN TOUCH</button>
                    </div>
                    <div class="col bg-dark pt-4 pb-4">
                        <h2 class=" ps-3 pb-5">About</h2>
                        <ul class="d-flex flex-column gap-3">
                            <li v-for="item in about">{{ item }}</li>
                          
                        </ul>
                    </div>
                    <div class="col bg-dark pt-4 pb-4">
                        <h2 class=" ps-3 pb-5">Transport</h2>
                        <ul class="d-flex flex-column gap-3">
                            <li v-for="item in transport">{{ item }}</li>
                        </ul>
                    </div>
                    <div class="col bg-dark pt-4 pb-4">
                        <h2 class=" ps-3 pb-5">Support</h2>
                        <ul class="d-flex flex-column gap-3">
                            <li v-for="item in support ">{{ item }}</li>
                        </ul>
                    </div>

                </div>
            </div>
        </div>
        <div class="bottom_footer d-flex justify-content-between">
            
            <p class=" align-self-center ps-3">Enjoy the low price. We are tracking any intention of piracy.</p>
            <p class=" align-self-center pe-3"> @2020 NEXGEN is Proudly Powered by <span style="color: aquamarine;">Codings</span></p>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
@use './scss/partials/variables.scss' as *;


footer{
    color: white;
}
.top_footer{
   
    background-color: $bg-primary;
    li{
        list-style-type: none
        ;
    }
}

.bottom_footer{
    height: 100px;
    background-color: black;
    padding-left: 2rem;
    padding-right: 2rem;
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
   

</style>