<template lang="html">
    <div>
        <Heador/>
        <Slider/>
        <Novice/>
        <Borrow/>
        <Money/>
        <Product/>
        <Life/>
        <Footor/>
        <Narbar/>
    </div>
</template>

<script>
	import Heador from "../public/header.vue"
	import Slider from "./hslider.vue"
	import Novice from "./novice.vue"
	import Borrow from "./borrow.vue"
	import Money from "./money.vue"
	import Product from "./product.vue"
	import Life from "./life.vue"
	import Footor from '../public/footer.vue'
	import Narbar from '../public/narbar.vue'
	export default {
		components:{
			Heador,
			Slider,
			Novice,
			Borrow,
			Money,
			Product,
			Life,
			Footor,
			Narbar
		}
	}
</script>

<style lang="scss" module>
  @import '../../css/reset.scss';
  .home{
    color: red;
    font-size: 80px;
  }
</style>
