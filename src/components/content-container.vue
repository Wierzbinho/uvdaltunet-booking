<template>
	<div class="container">
		<div class="content content--left">
			content left
		</div>
		<div class="content content--right">
			content-right
		</div>
	</div>
</template>

<script>
	export default {
		name: "contentContainer"
	}
</script>

<style>
	.container {
		display: inline-flex;
		width: 100%;
	}

	.content {
		padding: 30px;
	}

	.content--left {
		width: 70%;
		text-align: left;
	}

	.content--right {
		width: 30%;
	}
</style>