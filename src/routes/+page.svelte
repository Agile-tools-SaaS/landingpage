<script>
	import "@fontsource/roboto";
</script>
	<div class="container">
		<div class="logo"></div>
		<div>
		<h1><span>F</span><span>l</span><span>o</span><span>b</span><span>o</span><span>a</span><span>r</span><span>d</span></h1>
		<p>Application coming soon!</p>
		</div>
	</div>



<style lang="scss">
	@keyframes gradient {
	0% {
		background-position: 0% 50%;
	}
	50% {
		background-position: 100% 50%;
	}
	100% {
		background-position: 0% 50%;
	}
}
	:root {
		font-family: 'Roboto', sans-serif;
		background-color: rgb(196, 196, 196);
		color: white;
		background: linear-gradient(-45deg, #5293ee, red);
		background-size: 400% 400%;
		animation: gradient 15s ease infinite;
		height:100%;
		margin:0;

	}
	h1,p{margin:0;}
	h1{
		font-size: 40px;
		height:50px;
		display:flex;
		align-items: center;
		cursor:default;
	}
	@keyframes loadIn{
		from{opacity: 0;}
		to{opacity: 1;}
	}
	@keyframes loadOut{
		from{opacity: 1;}
		to{opacity: 0;}
	}
	h1>span{

		animation: loadIn 0.5s ease;
	}
	p{
		font-size:16px;
	}
	h1>span:hover{

		animation:loadOut 0.25s ease;
	}

	.container{
		display: flex;
		width:100vw;
		align-items: center;
		gap:30px;
		justify-content: center;
		transform: scale(1.25);
		width: 100vw;
		min-height: 80vh;

	}

	.logo{
		width:50px;
		height:65px;
		background: url("$lib/images/Floboard-logo.svg") no-repeat center;
		background-size:contain
	}
</style>
