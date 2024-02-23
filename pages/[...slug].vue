<template>
	<div class="page-not-found">page-not-found : 400</div>
</template>

<script lang="ts" setup>
	export interface IProps {
		title: string;
	}
	const props = withDefaults(defineProps<IProps>(), {
		title: "",
	});
</script>

<style lang="scss" scoped></style>
