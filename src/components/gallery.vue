<template>
	<div class="about">
		<div class="gallery" v-bind:style="styleObj">
		</div>
	</div>
</template>
<script>
let img = require('../assets/img/gallery.jpg');
	export default{
		data(){
			return {
				gallery:'gallery',
				styleObj:{
					backgroundImage:'url('+img+')'
				}
			}
		}
	}
</script>
<style lang="scss" scoped>
	.gallery{
		height: 300px;
		background-size: 100% 350px;
		background-repeat: no-repeat;

	}
	.about{
		height: 100%;
		background-color: #fff;
	}
</style>