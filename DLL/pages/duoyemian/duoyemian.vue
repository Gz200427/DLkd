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
					<view class="F">20,769.12</view>
					<view class="hong"></view>
					<view class="yi">
						<view class="yi1">
							贷款
						</view>
						<view class="yi2">
							51.34%
						</view>
					</view>
					<view class="lan"></view>
					<view class="er">
						<view class="er1">
							生活费
						</view>
						<view class="er2">
							18.20%
						</view>
					</view>
					<view class="zi"></view>
					<view class="san">
						<view class="san1">
							小摩托
						</view>
						<view class="san2">
							12.89%
						</view>
					</view>
					<view class="cheng"></view>
					<view class="si">
						<view class="si1">
							学习
						</view>
						<view class="si2">
							9.12%
						</view>
					</view>
					<view class="jian1">
						<image class="jian" src="../../static/6.png" mode=""></image>
					</view>
				</view>
				
			</view>
			<view class="TU2">
				<image class="TU3" src="../../static/4.png" mode=""></image>
				<view class="wenzi">
					·上次更新于 2020-12-28  23:45:12
				</view>
			</view>
			<view class="TU">
				<image class="TU1" src="../../static/3.png" mode=""></image>
			</view>
			<view class="zhu">
				<view class="bian"></view>
				<view class="diyi">
					<view class="Q">贷款</view>
					<view class="Q1">></view>
				</view>
				<view class="divLine"></view>
				<view class="dier">
					<view class="W">总资产(元)</view>
					<image class="W1" src="../../static/2.png" mode=""></image>
					<view class="W2">6</view>
					<view class="W3">存入笔数</view>
				</view>
				<view class="disan">
					<view class="E3">13,269.12</view>
					<view class="E1">51.34%</view>
					<view class="E2">总占比</view>
				</view>
			</view>
			<view class="zhu2">
				<view class="bian1"></view>
				<view class="diyi1">
					<view class="Q11">好好生活</view>
					<view class="Q111">></view>
				</view>
				<view class="T"></view>
				<view class="dier1">
					<view class="W11">总资产(元)</view>
					<!-- <image class="W111" src="../../static/2.png" mode=""></image> -->
					<view class="W21">6</view>
					<view class="W31">存入笔数</view>
				</view>
				<view class="disan1">
					<view class="E31">7500.00</view>
					<view class="E11">48.66%</view>
					<view class="E21">总占比</view>
				</view>
			</view>
			<view class="zhu3">
				<view class="bian2"></view>
				<view class="diyi2">
					<view class="Q2">贷款</view>
					<view class="Q12">></view>
				</view>
				<view class="divLine2"></view>
				<view class="dier2">
					<view class="W22">总资产(元)</view>
					<image class="W12" src="../../static/2.png" mode=""></image>
					<view class="W222">6</view>
					<view class="W32">存入笔数</view>
				</view>
				<view class="disan2">
					<view class="E32">13,269.12</view>
					<view class="E12">51.34%</view>
					<view class="E22">总占比</view>
				</view>
			</view>
			<button class="an" type="primary">+</button>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
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
	.jian1{
		width: 20px;
		height: 20px;
		/* position: absolute; */
		background-color: #007AFF;
		margin-left:300px;
		margin-top: 3px;
		/* bottom: 2px;
		right: 10px; */
		/* z-index: 1; */
	}
	.jian{
		width: 20px;
		height: 20px;
	}
	.cheng{
		width: 10px;
		height: 10px;
		background-color: #FFC000;
		margin-top: 10px;
		margin-left: 175px;
	}
	.si{
		width: 136px;
		height: 20px;
		/* background-color: #1B68FD; */
		margin-left: 195px;
		margin-top: -16px;
	}
	.si1{
		float: left;
		color: #808080;
		margin-top: 3px;
		font-size: 28rpx;
	}
	.si2{
		float: right;
		font-weight: bold;
	}
	.zi{
		width: 10px;
		height: 10px;
		background-color: #4379FF;
		margin-top: 10px;
		margin-left: 175px;
	}
	.san{
		width: 136px;
		height: 20px;
		/* background-color: #1B68FD; */
		margin-left: 195px;
		margin-top: -16px;
	}
	.san1{
		float: left;
		color: #808080;
		margin-top: 2px;
		font-size: 28rpx;
	}
	.san2{
		float: right;
		font-weight: bold;
	}
	.hong{
		width: 10px;
		height: 10px;
		background-color: #E5476F;
		margin-top: 20px;
		margin-left: 175px;
	}
	.yi{
		width: 136px;
		height: 20px;
		/* background-color: #1B68FD; */
		margin-left: 195px;
		margin-top: -16px;
	}
	.yi1{
		float: left;
		color: #808080;
		margin-top: 2px;
		font-size: 28rpx;
	}
	.yi2{
		float: right;
		font-weight: bold;
	}
	.lan{
		width: 10px;
		height: 10px;
		background-color:  #857CFF;
		margin-top: 10px;
		margin-left: 175px;
	}
	.er{
		width: 136px;
		height: 20px;
		/* background-color: #1B68FD; */
		margin-left: 195px;
		margin-top: -16px;
	}
	.er1{
		float: left;
		color: #808080;
		margin-top: 2px;
		font-size: 28rpx;
	}
	.er2{
		float: right;
		font-weight: bold;
	}
	.an{
		   position: absolute;
		            /* text-align: center; */
		            bottom: 0;
		            font-size: 30px;
		            color: #FFFFFF;
		            margin: 50px 0;
		            width: 50px;
		            height: 50px;
		            line-height: 45.5px;
		            background: #E0E0E0;
		            border-radius: 50px;
		            background-color: #1B68FD;
		            left: 90%;
		            transform: translateX(-50%);
	}
	.content {
		margin: 0 auto;
		width: 100vh;
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
		line-height: 180rpx;
		text-align: center;
		font-weight: 600;
	}
	.E{
		width: 200rpx;
		height: 50rpx;
		margin-top: -80%;
		margin-left: 115%;
		font-size: 30rpx;
		color: #808080;
		
	}
	.F{
		/* float: left; */
		width: 150rpx;
		height: 50rpx;
		margin-top: -2%;
		font-size: 25px;
		margin-left:115%;
		
	}
	.G1{
		width: 20px;
		height: 20px;
		margin-top: -6.5%;
		margin-left: 70%;
		position: absolute;
	}
	.TU{
		width: 96%;
		height: 80px;
		margin-top: 510rpx;
		position: absolute;
	}
	.TU1{
		width: 100%;
		height: 80px;
		margin-left: 2%;
		align-content: center;
	}
	.TU2{
		width: 96%;
		height:40px;
		background-color: #FFFFFF;
		margin-top:415rpx;
		position: absolute;
		margin-left: 2%;
		border-radius:10px;
	}
	.TU3{
		float: left;
		width: 28px;
		height: 20px;
		margin-left: 5%;
		margin-top: 2.5%;
		/* line-height: -50px; */
	}
	.wenzi{
		float: left;
		margin-left: 5%;
		line-height: 40px;
		
	}
	.zhu{
		width: 96%;
		height:125px;
		background-color: #FFFFFF;
		position: absolute;
		margin-top:690rpx;
		margin-left: 2%;
		border-left: 20px;
		border-radius: 10px;
		position: absolute;
	}
	.Q{
		float: left;
		font-size: 17px;
		line-height: 30px;
		margin-left: 5%;
		margin-top: 5px;
		font-weight: bold;
	}
	.Q1{
		float: right;
		font-size: 20px;
		margin-top: 5px;
		margin-right: 5%;
		color: #C8C7CC;
	}
	.divLine{
		float: left;
		 background: #E0E3DA;
		 width: 100%;
		 height: 3rpx;
		 margin-top: 7px;
		
	}
	.W{
		float: left;
		margin-top: 3%;
		margin-left: 8%;
		font-size: 30rpx;
		color: #808080;
	}
	.W1{
		float: left;
		width: 20px;
		height: 20px;
		font-size: 30px;
		margin-top: 3.3%;
		margin-left: 2%;
		/* position: absolute; */
	}
	.W2{
		margin-top: 3%;
		float: left;
		margin-left: 37%;
		font-weight: bold;
	}
	.W3{
		margin-top: 3.4%;
		float: right;
		margin-right: 7%;
		color: #808080;
		font-size: 28rpx;
		
	}
	.bian{
		width: 2%;
		height: 125px;
		background-color: #E5476F;
		border-radius: 80px 0 0 80px;
		position: absolute;
		
	}
	.E3{
		position: absolute;
		margin-top:23% ;
		margin-left: 8%;
		font-size: 20px;
		font-weight: bold;
		
	}
	.E1{
		/* float: left; */
		position: absolute;
		margin-left: 62%;
		margin-top:24%;
		font-weight: bold;
	}
	.E2{
		position: absolute;
		margin-top:24% ;
		/* float: right; */
		margin-left: 81.5%;
		color: #808080;
		font-size: 28rpx;
	}
	.zhu2{
		width: 96%;
		height:125px;
		background-color: #FFFFFF;
		position: absolute;
		margin-top: 960rpx;
		margin-left: 2%;
		border-left: 20px;
		border-radius: 10px;
	}
	.Q11{
		float: left;
		font-size: 17px;
		line-height: 30px;
		margin-left: 5%;
		margin-top: 5px;
		font-weight: bold;
	}
	.Q111{
		float: right;
		font-size: 20px;
		margin-top: 5px;
		margin-right: 5%;
		color: #C8C7CC;
	}
	.T{
		float: left;
		 background: #E0E3DA;
		 width: 100%;
		 height: 3rpx;
		 margin-top: 7px;
		
	}
	.W11{
		float: left;
		margin-top: 3%;
		margin-left: 8%;
		font-size: 30rpx;
		color: #808080;
	}
	.W111{
		float: left;
		width: 20px;
		height: 20px;
		font-size: 30px;
		margin-top: 3.3%;
		margin-left: 2%;
		position: absolute;
	}
	.W21{
		margin-top: 3%;
		float: left;
		margin-left: 43%;
		font-weight: bold;
	}
	.W31{
		margin-top: 3.4%;
		float: right;
		margin-right: 8%;
		color: #808080;
		font-size: 28rpx;
		
	}
	.bian1{
		width: 2%;
		height: 125px;
		background-color: #857CFF;
		border-radius: 80px 0 0 80px;
		position: absolute;
		
	}
	.E31{
		position: absolute;
		margin-top:23% ;
		margin-left: 8%;
		font-size: 20px;
		font-weight: bold;
		
	}
	.E11{
		float: left;
		margin-left: 62%;
		margin-top:5%;
		font-weight: bold;
	}
	.E21{
		margin-top:5% ;
		float: right;
		margin-right: 8.3%;
		color: #808080;
		font-size: 28rpx;
	}
	.zhu3{
		width: 96%;
		height:125px;
		background-color: #FFFFFF;
		position: absolute;
		margin-top:1230rpx;
		margin-left: 2%;
		border-left: 20px;
		border-radius: 10px;
		position: absolute;
	}
	.Q2{
		float: left;
		font-size: 17px;
		line-height: 30px;
		margin-left: 5%;
		margin-top: 5px;
		font-weight: bold;
	}
	.Q12{
		float: right;
		font-size: 20px;
		margin-top: 5px;
		margin-right: 5%;
		color: #C8C7CC;
	}
	.divLine2{
		float: left;
		 background: #E0E3DA;
		 width: 100%;
		 height: 3rpx;
		 margin-top: 7px;
		
	}
	.W22{
		float: left;
		margin-top: 3%;
		margin-left: 8%;
		font-size: 30rpx;
		color: #808080;
	}
	.W12{
		float: left;
		width: 20px;
		height: 20px;
		font-size: 30px;
		margin-top: 3.3%;
		margin-left: 2%;
		/* position: absolute; */
	}
	.W222{
		margin-top: 3%;
		float: left;
		margin-left: 37%;
		font-weight: bold;
	}
	.W32{
		margin-top: 3.4%;
		float: right;
		margin-right: 7%;
		color: #808080;
		font-size: 28rpx;
		
	}
	.bian2{
		width: 2%;
		height: 125px;
		background-color: #4379FF;
		border-radius: 80px 0 0 80px;
		position: absolute;
		
	}
	.E32{
		position: absolute;
		margin-top:23% ;
		margin-left: 8%;
		font-size: 20px;
		font-weight: bold;
		
	}
	.E12{
		/* float: left; */
		position: absolute;
		margin-left: 62%;
		margin-top:24%;
		font-weight: bold;
	}
	.E22{
		position: absolute;
		margin-top:24% ;
		/* float: right; */
		margin-left: 81.5%;
		color: #808080;
		font-size: 28rpx;
	}
</style>
