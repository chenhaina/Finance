<template lang="html">
	<article class="">
		<Slider :items="items" :cname="$style.slider"/>
	</article>
</template>

<script>
	import Slider from "../core/slider.vue"
	export default{
		components:{
			Slider,
		},
		data(){
			return{
				items:[{
					href:'Home',
					src:'//img12.360buyimg.com/jrpmobile/jfs/t11149/181/856008463/68797/dc303e9/59f97baeN3cdae084.jpg?width=750&height=400'
				},
				{
					href:'Home',
					src:'//img12.360buyimg.com/jrpmobile/jfs/t11149/181/856008463/68797/dc303e9/59f97baeN3cdae084.jpg?width=750&height=400'
				},
				],
//				options:{
//					pagination:{
//						el:".swiper-pagination",
//						clickable:true
//						
//					}
//				},
			}
		}
		
	}
</script>

<style lang="scss" module>
	@import "../../css/element.scss";
	.slider{
		margin-top:120px;
		width: 100%;
		height: 344px;
		img{
			width: 100%;
			height: 100%;
		}
	}

	
</style>