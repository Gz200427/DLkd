<template>
	<view class="content">
		<view class="A">
			<view class="B">
				<view class="C">
					<view class="D">资产配比</view>
				</view>
				<view class="E">总资产(元)</view>
				<view class="G">
					<image class="G1" src="../../static/2.png" mode=""></image>
				</view>
				<view class="F">0.00</view>
			</view>
			
		</view>
		<view class="TU">
			<image class="TU1" src="../../static/3.png" mode=""></image>
		</view>
		 <button class="an" type="primary"> 新建计划</button>
	</view>
	
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello'
			}
		},
		onLoad() {

		},
		methods: {

		}
	}
</script>

<style>
	*{
		margin: 0;
		padding: 0;
	}
	.content {
		margin: 0 auto;
		width: 100%;
		height: 100vh;
		background-color: #E3E3E3;
	}
	.A{
		display: flex;
		background-color: #FFFFFF;
		width: 96%;
		height: 200px;
		position: absolute;
		margin:0 auto;
		border-radius: 20px;
		margin-left: 2%;
		align-content: center;
	}
	.B{
		width: 150px;
		    height: 150px;
		    border-radius: 50%;
		    background: #E3E3E3;
			margin-top: 6%;
			margin-left: 5%;
		    /* background-image: linear-gradient(to right, transparent 50%, #655 0); */
	}
	.C{
		width: 90px;
		height: 90px;
		margin-top: 19.5%;
		margin-left: 19.5%;
		background: #FFFFFF;
		border-radius: 50%;
	}
	.D{
		width: 150rpx;
		height: 50rpx;
		margin:auto;
		/* margin-top: 10px; */
		line-height: 180rpx;
		text-align: center;
		font-weight: bold;
		/* background-color: #007AFF; */
		/* margin-top: 50px; */
	}
	.E{
		/* float: left; */
		width: 200rpx;
		height: 50rpx;
		margin-top: -80%;
		margin-left: 135%;
		font-size: 30rpx;
		color: #808080;
		
	}
	.F{
		float: left;
		width: 150rpx;
		height: 50rpx;
		margin-top: -2%;
		font-size: 25px;
		margin-left:135%;
		
	}
	.G1{
		width: 20px;
		height: 20px;
		margin-top: -6.5%;
		margin-left: 77%;
		position: absolute;
	}
	.TU{
		width: 96%;
		height: 80px;
		margin-top: 410rpx;
		position: absolute;
	}
	.TU1{
		/* display: flex; */
		/* justify-content: center; */
		/* background-color: #FFFFFF; */
		/* width: 350px; */
		width:100%;
		height: 80px;
		/* position: absolute; */
		/* margin:0 auto; */
		/* border-radius: 20px; */
		/* margin-top: 56%; */
		margin-left: 2%;
		/* margin-right: 3%; */
		align-content: center;
	}
	.an{
		   position: absolute;
		            text-align: center;
		            bottom: 0;
		            font-size: 16px;
		            color: #FFFFFF;
		            margin: 25px 0;
		            width: 335px;
		            height: 45px;
		            line-height: 45.5px;
		            background: #E0E0E0;
		            border-radius: 50px;
		            background-color: #1B68FD;
		            left: 50%;
		            transform: translateX(-50%);
	}

</style>
