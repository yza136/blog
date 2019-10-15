<template>
	<el-header>
		<el-container class="">
			    <h1 class="img"><img src="../assets/w-logo.png"/></h1>
				<el-menu :default-active="activeIndex" class="el-menu-demo" mode="horizontal" @select="handleSelect">
					<el-menu-item index="1"><router-link to="/">首页</router-link></el-menu-item>
					<el-menu-item  index="2"><router-link to="">发现</router-link></el-menu-item>
					<el-menu-item index="3" ><router-link to="">消息</router-link></el-menu-item>
					<el-menu-item index="4"><router-link to="/Heder">登录</router-link></el-menu-item>
					<el-menu-item index="5"><router-link to="/Heder">注册</router-link></el-menu-item>
				</el-menu>
			
		</el-container>
	</el-header>
</template>

<script>
export default{
		name: 'header'
	}
</script>

<style scoped="" lang="scss">
	
	h1{
		margin:0;
		img{
			line-height: 3.75rem;
			height: 100%;
		}
		height: 3.75rem;
	}
	.el-header{
		padding:0.46875rem ;
		background: #FFFFFF;
		height:4.6875rem!important;
		box-shadow: 0 2px 2px 0 rgba(0,0,0,.1);
	}
	.el-menu{
	    border: none;
	}
</style>
