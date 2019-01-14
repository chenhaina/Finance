<template lang="html">
    <div>
        <Heador/>
        <Slider/>
        <Ads/>
        <Money/>
        <Adb/>
        <Finance/>
         <Adc/>
        <Footor cname="mfooter"/>
        <Narbar/>
    </div>
</template>

<script>
	import Heador from "../public/header.vue"
	import Slider from "./mslider.vue"
	import Footor from '../public/footer.vue'
	import Narbar from '../public/narbar.vue'
	import Ads from './ads.vue'
	import Money from './money.vue'
	import Adb from './adb.vue'
	import Adc from './adc.vue'
	import Finance from './finance.vue'
	export default {
		components:{
			Heador,
			Slider,
			Ads,
			Money,
			Adb,
			Adc,
			Finance,
			Footor,
			Narbar
		}
	}
</script>

<style lang="scss">
    .mfooter{
    	ul{
    		li:first-child{
    			display: none;
    		}
    	}
    }
</style>
