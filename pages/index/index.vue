<template>
	<view class="content">
		<button type="default" @click="toLink()">进入播放器</button>
	</view>
</template>

<script>
	export default {
		data() {
			return {
			}
		},

		methods: {
			toLink(link){
				uni.navigateTo({
				    url: '/pages/live/live'
				});
			}
		}
	}
</script>

<style>
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
</style>
