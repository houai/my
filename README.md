<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>爱你么么哒</title>
	<style>
	.love{
		position: relative;
		width:500px;
		height:500px;
		margin:200px auto;
		animation:myframes 3s infinite;
	}
	@keyframes myframes{
		0%{transform:scale(0.5);}
		50%{transform:scale(3);}
		100%{transform:scale(0.5);}
	}
	.lf-love{
		width:300px;
		height:300px;
		border-radius:50%;
		background: pink;
	}
	.rgt-love{
		width:300px;
		height:300px;
		border-radius:50%;
		background: pink;
	}
	.rgt-love{
		position: absolute;
		top:0;
		right: 0;
	}
	.btm-love{
		position: absolute;
		top:100px;
		right: 0;
		left: 0;
		margin:auto;
		width:300px;
		height:300px;
		background: pink;
		transform:rotate(45deg); 
	}
	h1{
		position: absolute;
		top:160px;
		left:0;
		right:0;
		margin:auto;
		width: 100px;
		height:50px;
		color:white;
		text-align: center;
		line-height: 50px;
		background: pink;
		font-size:30px;
	}

	</style>

</head>
<body>
	<div class="love">
		<div class="lf-love"></div>
		<div class="rgt-love"></div>
		<div class="btm-love"></div>
		<h1>陈婷婷love</h1>
	</div>
	<script>
		alert("陈婷婷傻逼");
		alert("快说你是不是傻逼");
	</script>
	
</body>
</html>
