<template>
	<div class="test">
		{{msg}}
	</div>
</template>

<script>
	export default {
		name: 'test',
		data() {
			return {
				msg: "你好啊"
			}
		},
		mounted:function(){
			mui.toast(123);
		}
	}
</script>

<style>

</style>