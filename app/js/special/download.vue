<template lang="html">
	<Panel :class="$style.panel" title="下载APP">
		<section :class="$style.content">
			<div class="">
				
			</div>
			<p>立即下载</p>
			<p>copyright</p>
		</section>
	</Panel>
</template>

<script>
	import Panel from "../core/panel.vue"
	export default{
		components:{
			Panel,
		},
	}
</script>

<style lang="scss" module>
	@import "../../css/element.scss";
	.panel{
		@include panel;
		margin:0!important;	
		>h4{
			display: none;
		}	
		.content{
			@include flex;
			justify-content: center;
			align-items: center;
			width: 100%;
			height: 1136px;
			div{
				background: url()center center no-repeat;
				width: 600px;
				height: 800px;
				background-size: 100% auto;
				margin-top: -200px;
			}
			p{
				@include btn($size:32px,$color:#fff,$bgcolor:#f1443e,$padding:5px,$radius:5px);
				height: 100px;
				line-height: 100px;
				width: 471px;
				position: fixed;
				bottom: 130px;
				
			}
		}
	}
</style>