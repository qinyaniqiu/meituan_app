<template>
	<view >
		<van-row custom-class="top">
			<van-col span="24">
				<view class="top-menu" @click="linkTo('/pages/address/address')">
					<van-icon name="location-o" custom-style="font-weight:700;margin-right:5rpx;" size="16px" />
					<text>银座中心1号楼</text>
					<van-icon name="arrow" custom-style="font-weight:700;margin-left:5rpx" size="10px" />
				</view>
			</van-col>
		</van-row>
		<van-row custom-class="body">
			<van-col span="24">
				<van-search value="" shape="round" placeholder="请输入搜索关键词" custom-class="search" field-class="field-class"
				 background="#F2F2F2" />
			</van-col>
			<van-col span="24">
				<van-row gutter="5">
					<van-col><text class="menu-botton">虾锅</text></van-col>
					<van-col><text class="menu-botton">芝士炸鸡</text></van-col>
					<van-col><text class="menu-botton">茶鸡蛋</text></van-col>
					<van-col><text class="menu-botton">祝寿蛋糕</text></van-col>
					<van-col><text class="menu-botton">米线</text></van-col>
					<van-col><text class="menu-botton">徽菜</text></van-col>
				</van-row>
			</van-col>
			<van-col span="24">
				<swiper style="margin-top: 10px; background-color: #FFFFFF; border-radius: 10px; padding: 6px 0px;" 
				indicator-dots="true" indicator-active-color="#ffa900"
				>
					<swiper-item >
						<view class="daohang">
							<view>
								<view class="tb" style="background-image: linear-gradient(to top,#F3563F,#FE9452);">
									<image src="../../static/icon/ms.png"></image>
								</view>
								<text>美食</text>
							</view>
							<view>
								<view class="tb" style="background-image: linear-gradient(to top,#187CD3,#5CBAF3);">
									<image src="../../static/icon/cs.png"></image>
								</view>
								<text>超市便利</text>
							</view>
							<view>
								<view class="tb" style="background-image: linear-gradient(to top,#6DC840,#94E82B);">
									<image src="../../static/icon/sg.png"></image>
								</view>
								<text>蔬菜水果</text>
							</view>
							<view>
								<view class="tb" style="background-image: linear-gradient(to top,#FDC85F,#FEDC5D);">
									<image src="../../static/icon/yx.png"></image>
								</view>
								<text>买药</text>
							</view>
							<view>
								<view class="tb" style="background-image: linear-gradient(to top,#F1A75B,#FBB957);">
									<image src="../../static/icon/pt.png"></image>
								</view>
								<text>跑腿代购</text>
							</view>
						</view>
						<view class="daohang">
							<view>
								<view class="tb" style="background-image: linear-gradient(to top,#51B8D1,#71DFD6);">
									<image src="../../static/icon/bz.png"></image>
								</view>
								<text>包子粥铺</text>
							</view>
							<view>
								<view class="tb" style="background-image: linear-gradient(to top,#FDC85F,#FEDC5D);">
									<image src="../../static/icon/mb.png"></image>
								</view>
								<text>早餐</text>
							</view>
							<view>
								<view class="tb" style="background-image: linear-gradient(to top,#F3563F,#FE9452);">
									<image src="../../static/icon/hb.png"></image>
								</view>
								<text>汉堡披萨</text>
							</view>
							<view>
								<view class="tb" style="background-image: linear-gradient(to top,#CA92D5,#E980E9);">
									<image src="../../static/icon/cqg.png"></image>
								</view>
								<text>超值联盟</text>
							</view>
							<view>
								<view class="tb" style="background-image: linear-gradient(to top,#F1A75B,#FBB957);">
									<image src="../../static/icon/zkj.png"></image>
								</view>
								<text>必囤好券</text>
							</view>
						</view>
					</swiper-item>
					<swiper-item >
						<view class="daohang">
							<view>
								<view class="tb" style="background-image: linear-gradient(to top,#F3563F,#FE9452);">
									<image src="../../static/icon/ms.png"></image>
								</view>
								<text>美食</text>
							</view>
							<view>
								<view class="tb" style="background-image: linear-gradient(to top,#187CD3,#5CBAF3);">
									<image src="../../static/icon/cs.png"></image>
								</view>
								<text>超市便利</text>
							</view>
							<view>
								<view class="tb" style="background-image: linear-gradient(to top,#6DC840,#94E82B);">
									<image src="../../static/icon/sg.png"></image>
								</view>
								<text>蔬菜水果</text>
							</view>
							<view>
								<view class="tb" style="background-image: linear-gradient(to top,#FDC85F,#FEDC5D);">
									<image src="../../static/icon/yx.png"></image>
								</view>
								<text>买药</text>
							</view>
							<view>
								<view class="tb" style="background-image: linear-gradient(to top,#F1A75B,#FBB957);">
									<image src="../../static/icon/pt.png"></image>
								</view>
								<text>跑腿代购</text>
							</view>
						</view>
						<view class="daohang">
					</swiper-item>
				</swiper>
			</van-col>
		</van-row>

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
			linkTo(url) {
				console.log("111")
				uni.navigateTo({
					url: url
				})
			}
		}
	}
</script>

<style>
	/* @/static/css/index.css: 其中@代表项目根目录 */
	@import "@/static/css/index.css";
</style>
