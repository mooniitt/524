<template>
	<div class="vnav">
		<div class="wr">
			<ul>
				<li><a href="#">首页</a></li>
				<li><a href="#">番剧</a></li>
				<li><a href="#">动漫</a></li>
				<li><a href="#">音乐</a></li>
				<li><a href="#">. . .</a></li>
			</ul>
			<div class="nv-search">
				
			</div>
		</div>
	</div>
</template>

<script>
	export default{
		name:'vnav'
	}
</script>

<style scope>
	.vnav{
		width: 100%;
		height: 48px;
		box-shadow: 0 1px 1px rgba(0,0,0,0.1);
		background-color: #fff;
	}
	.wr{
		height: 48px;
		position: relative;
		max-width: 1160px;
		min-width: 980px;
		margin:0 auto;
	}
	.wr ul{
		list-style-type: none; 
		width: 60%;
		display: block;
		float: left;
	}
	.wr ul li{
		display: inline-block;
		line-height: 48px;
		height: 48px;
		margin-right: 48px;
		text-align: center;
		font-size: 18px;
		width: 52px;
	}
	.wr ul li::after{
		content:'';
		display: block;
		height: 3px;
		background-color: #FF6A38;
		width: 0px;
		transition: all .2s ease;
	}
	.wr ul li:hover::after{
		width: 52px;
	}
	.wr ul li a{
		display: block;
		text-decoration: none;
		color: #234;
		line-height: 48px;
	}
	.nv-search{
		float: right;
		width: 39%;
		height: 48px;
		/*border-left-color: grey;
		border-left-width: 2px;
		border-left-style: solid;*/
	}
</style>