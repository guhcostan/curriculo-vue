<template lang="pug">
	#sobre
		el-container
			el-row(type="flex" justify="center")
				el-col(span="24")
					.titulo Sobre
</template>

<script>
export default {
	name: 'Sobre'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
	#sobre {
		height: 100vh;
		padding: 100px 0 0 0!important;

		.el-row {

			width: 100%;

			.el-col {

				.titulo {
					text-align: center;
					width: 100%;
					font-size: 50px;
				}
			}
		}
	}


</style>
