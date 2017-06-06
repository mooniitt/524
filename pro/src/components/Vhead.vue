<template>
	<div class="vhead">
		<div class="nv-bg">
			<div class="nv-master">
				<div class="container">
					<div class="nv-logo">
						<p>PiliPili Game!</p>
					</div>
					<div class="nv-sign">
						<a href="#login">登录</a>
						<a href="#logout">注册</a>
					</div>
				</div>
			</div>			
		</div>
	</div>
</template>

<script>
	export default{
		name:'vhead'
	}
</script>

<style scope>
	.nv-bg{
		background-image: url("../assets/bg.jpg"); 
		background-repeat:no-repeat;
		background-position: center center;
		position: relative;
		width: 100%;
		height: 180px;
	}
	.nv-master{
		height: 42px;
		width: 100%;
		position: absolute;
		left: 0px;
		top: 0px;
		background-color: rgba(0,0,0,0.6);
	}
	.container{
		margin: 0 auto;
		max-width: 1160px;
		min-width: 980px;
		height: 42px;
		position: relative;
	}
	.nv-logo {
		float: left;
		width: 200px;
		height: 42px;
	}
	.nv-logo p {
		color: #FF6A38;
		line-height: 42px;
		font-size: 18px;
	}
	.nv-sign {
		float: right;
		width: 200px;
		height: 42px;
		/*background-color: red;*/
	}
	.nv-sign a{
		text-decoration: none;
		display: inline-block;
		height: 42px;
		line-height: 42px;
		color: #fff;
		padding-right: 30px;
	}
	.nv-sign a:linked,.nv-sign a:active,.nv-sign a:hover,.nv-sign a:visited{
		color: #fff;
	}
</style>