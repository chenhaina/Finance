<template lang="html">
    <div>
        <Heador/>
        <Slider/> 
        <Welfare/>
        <Sevice/>
        <Footor/>
        <Narbar/>
    </div>
</template>

<script>
	import Heador from "../public/header.vue"
	import Slider from "./islider.vue"
	import Sevice from "./sevice.vue"
	import Footor from '../public/footer.vue'
	import Narbar from '../public/narbar.vue'
	import Welfare from './welfare.vue'
	export default {
		components:{
			Heador,
			Slider,
			Welfare,
			Sevice,
			Footor,
			Narbar
		}
	}
</script>

<style lang="scss">
</style>
