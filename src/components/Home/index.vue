<template>
  <div class="content-box">
	  <el-container class="">
	  	<el-main>
			
		</el-main>
		<el-aside>
			<div class="">
				<ul class="title">
					<li>账号登录</li>
					<li>安全登录</li>
				</ul>
				<div class="">
					<div class="">
						<input type="text"/>
					</div>
					<div>
						<input  type="password"/>
					</div>
				</div>
			</div>
		</el-aside>
	  </el-container>
  </div>
</template>

<script>
export default {
  name: 'Home' 
}
</script>


<style lang="scss" scoped="">
	.content-box{
		margin-top:1.5rem;
	}
    .el-aside{
		background: #fff;
	}
	.title{
		padding:0px;
		display:flex;
		li{
			list-style: none;
			display: inline-block;
			flex: 1;
			text-align: center;
			font-size: 1.125rem;
		}
	}
</style>
