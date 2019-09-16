<template lang="html">
    <div :class="$style.home">
        <Heador></Heador>
        <Slider></Slider>
        <Novice></Novice>
        <Borrow></Borrow>
        <Money></Money>
        <Product></Product>
        <Life></Life>
        <Footer1></Footer1>
        <Navbar></Navbar>
    </div>
</template>

<script>
import Heador from '../public/header.vue'
import Slider from './hsilder.vue' 
import Novice from './novice.vue' 
import Borrow from './borrow.vue' 
import Money from './money.vue' 
import Life from './life.vue' 
import Product from './product' 
import Footer1 from '../public/footer' 
import Navbar from '../public/navbar' 

export default {
  components:{
    Heador,
    Slider,
    Novice,
    Borrow,
    Money,
    Life,
    Product,
    Footer1,
    Navbar,
  }
}
</script>

<style lang="scss" module>

</style>
