<template>
	<div class="table">
		<h1>Page Developing</h1>
	</div>
</template>

<script setup>
import { onMounted } from 'vue'
const props = defineProps({
	dataList: [],
})
onMounted(() => {
	setTimeout(() => {
		console.log(props.dataList)
	}, 1000)
})
</script>

<style lang="less" scoped></style>
