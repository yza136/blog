<template>
  <div id="app">
		<Header/>
		<router-view ></router-view>
  </div>
</template>

<script>
import Header from "./components/Header"
export default {
  name: 'App',
  components:{
	  Header
  }
}
</script>


<style lang="scss">
	body{
		min-width: 1200px;
		margin: 0;
		padding: 0;
		background: #f4f5f8;
	}
	
	.el-container{
		justify-content: space-between;
		width: 1100px;
		margin: 0 auto;
	}
</style>
