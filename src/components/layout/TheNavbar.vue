<template>
	<div id="nav">
		<div class="header">	
			<router-link to="/">Home</router-link> |
			<router-link to="/signin">Sign in</router-link> |
			<router-link to="/signup">Sign up</router-link>
		</div>
	</div>
</template>

<script>
export default {

}
</script>

<style scoped>
.header {
	width: 100%;
	height: 40px;
	background-color: darkslategray;
}
</style>

