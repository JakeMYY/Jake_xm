<template>
	<div>
		<mt-header title="九期信息管理系统" ref="n1"></mt-header>
		<router-view></router-view>
		<nav class="mui-bar mui-bar-tab" ref="n2">
			<router-link :to="{name:'Home'}" class="mui-tab-item mui-active" href="#tabbar">
				<span class="mui-icon icon-shouye"></span>
				<span class="mui-tab-label">首页</span>
			</router-link>
			<router-link :to="{name:'vip'}" class="mui-tab-item">
				<span class="mui-icon icon-huiyuan1"></span>
				<span class="mui-tab-label">会员</span>
			</router-link>
			<router-link :to="{name:'shopcart'}" class="mui-tab-item">
				<span class="mui-icon icon-gouwucheman">
					<span class="mui-badge">9</span>
				</span>
				<span class="mui-tab-label">购物车</span>
			</router-link>
			<router-link :to="{name:'search'}" class="mui-tab-item">
				<span class="mui-icon icon-work-search"></span>
				<span class="mui-tab-label">查找</span>
			</router-link>
		</nav>
	</div>
</template>
<script>
//引入字体css
import './static/css/iconfont.css';
export default {
	data() {
		return {

		}
	}
}
</script>
<style lang="">
/* @import  url('./static/css/iconfont.css'); */
</style>