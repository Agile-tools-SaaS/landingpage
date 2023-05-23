<div class="parent-container">
	<div class="container">
		<h1>Agile SaaS tool</h1>
		<p>Application coming soon!</p>
	</div>
</div>

<style lang="scss">
	:root {
		font-family: Arial, Helvetica, sans-serif;
		background-color: rgb(60, 60, 60);
		color: white;
	}
	.parent-container {
		display: flex;
		justify-content: center;
		width: 100%;
		min-height: 100%;
	}
	.container {
		width: clamp(300px, 100%, 800px);
		height: 100%;
		padding: 20px;

		& * {
			margin: 0;
		}
	}
</style>
