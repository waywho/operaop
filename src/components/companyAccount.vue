<template>
	<div>
		<h1>Hello World</h1>
		<h2>{{ company.name }}</h2>
	</div>
</template>

<script>
export default {
	data() {
		return {
			company: {
				name: "MY OPERA"
			}
		}
	}
}
</script>

<style scoped>
#nav {
  position: absolute;
}
</style>
