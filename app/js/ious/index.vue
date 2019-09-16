<template>
    <div>
        <Heador></Heador>
        <Slider></Slider>
        <Welfare></Welfare>
        <Service></Service>
        <Footor></Footor>
        <Navbar></Navbar>
    </div>
</template>

<script>
import Heador from "../public/header.vue"
import Footor from "../public/footer.vue"
import Navbar from "../public/navbar.vue"
import Slider from "./islider.vue"
import Welfare from "./welfare.vue"
import Service from "./service.vue"
    export default {
        components:{
            Heador,
            Footor,
            Navbar,
            Slider,
            Welfare,
            Service
        }
    }
</script>

<style lang="scss" scoped>

</style>