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
					src:'//img12.360buyimg.com/jrpmobile/jfs/t1/28682/28/4117/80887/5c2f0119E7edb11c7/36801e10c2d01269.jpg?width=750&height=320'
				},
				{
					href:'Home',
					src:'//img12.360buyimg.com/jrpmobile/jfs/t1/6240/6/12194/46685/5c2f01abE170b3a32/1ba77c413034ac28.jpg?width=750&height=320'
				},
				{
					href:'Home',
					src:'//img12.360buyimg.com/jrpmobile/jfs/t1/15966/19/4141/46410/5c2f01caE7e9495ea/29b0eb4689f1f7ad.jpg?width=750&height=320'
				},
				{
					href:'Home',
					src:'//img12.360buyimg.com/jrpmobile/jfs/t1/26355/33/4136/139307/5c2f01eaEb4d272ee/b8be74bbe602533a.jpg?width=750&height=320'
				}],
			}
		}
		
	}
</script>

<style lang="scss" module>
	@import "../../css/element.scss";
	.slider{
		margin-top:120px;
		img{
			width: 100%;
		}
	}

	
</style>