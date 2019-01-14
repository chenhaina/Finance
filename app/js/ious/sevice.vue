<template lang="html">
	<Panel :class="$style.panel" title="更多服务">
		<section :class="$style.content">
		   <div :class="$style.item" v-for="item in enters" :key="item.href">
		   	  <router-link :to="{name:item.href}">
		   	  	<img :src="item.img" :alt="item.title"/>
		   	  	<h4>{{item.title}}</h4>
		   	  </router-link>
		   </div>
		</section>
	</Panel>
</template>

<script>
	import Panel from "../core/panel.vue"
	export default{
		components:{
			Panel,
		},
		data(){
			return{
				enters:[{
					href:"Home",
					img:"//img12.360buyimg.com/jrpmobile/jfs/t3991/64/2521945388/12110/93c0139/58d1e462Ncf294123.png?width=132&height=132",
					title:"优惠券",
				},
				{
					href:"Home",
					img:"//img12.360buyimg.com/jrpmobile/jfs/t5590/252/875247023/17343/946aa72c/59224650N0f7ffc92.png?width=132&height=132",
					title:"领红包",
				},
				{
					href:"Home",
					img:"//img12.360buyimg.com/jrpmobile/jfs/t4393/329/2180608902/13217/c88c0cec/58ec9dcdN1534e2d7.png?width=132&height=132",
					title:"抢钢镚",
				},
				{
					href:"Home",
					img:"//img12.360buyimg.com/jrpmobile/jfs/t1/3924/28/657/3552/5b9240dbE60256c31/78b52d5ab675f800.png?width=132&height=132",
					title:"领京豆",
				},{
					href:"Home",
					img:"//img12.360buyimg.com/jrpmobile/jfs/t5488/298/1036263348/12073/b4f4de97/590ac8e8Ne9def22e.png?width=135&height=135",
					title:"白条提额",
				},
				{
					href:"Home",
					img:"//img12.360buyimg.com/jrpmobile/jfs/t4393/329/2180608902/13217/c88c0cec/58ec9dcdN1534e2d7.png?width=132&height=132",
					title:"抢钢镚",
				},
				{
					href:"Home",
					img:"//img12.360buyimg.com/jrpmobile/jfs/t1/3924/28/657/3552/5b9240dbE60256c31/78b52d5ab675f800.png?width=132&height=132",
					title:"领京豆",
				},{
					href:"Home",
					img:"//img12.360buyimg.com/jrpmobile/jfs/t5488/298/1036263348/12073/b4f4de97/590ac8e8Ne9def22e.png?width=135&height=135",
					title:"白条提额",
				}
				]
			}
		}
		
	}
</script>

<style lang="scss" module>
	@import "../../css/element.scss";
	.panel{
		.content{
			@include list(row);
			background: #fff;
			padding-top: 40px;
			padding-bottom: 20px;
			justify-content: space-around;
			a{
				text-decoration: none;
			}
			.item{
				width:25%;
				text-align: center;
				height: 144px;
				margin-bottom: 40px;
				img{
					display:inline-block;
					width: 90px;
					height: 90px;					
				}
				h4{
					color:#000;
					font-size: 26px;
					margin-top: 12px;
				}
			}
			
		}
	}	
</style>