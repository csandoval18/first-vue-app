<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
	<header>
		<nav>
			<img src="@/assets/logo.svg" alt="" />
			<div class="options">
				<RouterLink to="/">Home</RouterLink>
				<RouterLink to="/about">About</RouterLink>
			</div>
		</nav>
	</header>
</template>

<style scoped>
nav {
	display: flex;
	align-items: center;
	justify-content: center;
	/* background: #252525; */
	background-color: #7bbeeb;
	padding-inline: 1rem;
	height: 3rem;
}

img {
	height: 2rem;
	width: 2rm;
}

.options {
	margin-left: auto;
	display: flex;
	gap: 1rem;
}
</style>
