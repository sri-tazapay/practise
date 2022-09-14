<template>
	<h2> Component E </h2>
	<ComponentF />
</template>

<script>
import ComponentF from "@/components/ComponentF.vue"
export default {
	name : "ComponentE",
	components : {
		ComponentF
	},
}
</script>

<style>
</style>