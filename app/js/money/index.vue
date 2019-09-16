<template>
    <div>
        <Heador/>
        <Slider/>
        <Ada/>
        <Money/>
        <Finance/>
        <Adc/>
        <Footor cname="mfooter"/>
        <Navbar/>
    </div>
</template>

<script>
    import Heador from "../public/header.vue"
    import Footor from "../public/footer.vue"
    import Navbar from "../public/navbar.vue"
    import Slider from "./mslider"
    import Ada from "./ada"
    import Adb from "./adb"
    import Adc from "./adc"
    import Money from "./money"
    import Finance from "./finance"

    export default {
        components:{
            Heador,
            Footor,
            Navbar,
            Slider,
            Ada,
            Adb,
            Adc,
            Money,
            Finance,
        }
    }
</script>

<style lang="scss">
    .mfooter{
        margin-top: 0 !important;
        ul{
            li:first-child{
                display: none;
            }
        }
    }
</style>