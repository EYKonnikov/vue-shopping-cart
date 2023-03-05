<template>
	<div>Hello main page {{count}}</div>
</template>

<script>
	export default {
		name: "MainPage",
		
		computed: {
			count() {
				return this.$store.state.count
			}
		}
	}
</script>

<style>
	
</style>