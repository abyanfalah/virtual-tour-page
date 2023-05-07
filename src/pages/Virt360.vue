<script setup>
import { getCurrentInstance } from 'vue';


const componentName = getCurrentInstance()?.type.__name;

</script>

<template>
	<!-- <h1>Virtual tour make "{{ componentName }}"</h1> -->

	<iframe class="rounded"
					height="100%"
					width="100%"
					allowfullscreen=""
					frameborder="0"
					src="https://virtualtoureasy.com/tour/viewer/index.php?v=UKsy7lPFd8HYr415NOTq"
					allowcontrols="true"
					allowsceneselector="true"
					allowaudio="true"></iframe>
</template>

<style scoped>
.full {
	min-height: 100%;
	width: 100%;
}

.frame-view {
	height: 100%;
	width: 100%;
	background-color: red;
}
</style>