<script>
	import logo from '../assets/logo.svg';
</script>

<div class="container">
	<div>
		<img src="{logo}">
	</div>
	<slot />
</div>

<style>
	.container {
		max-width: 860px;
		padding: 2em;
		font-family: sans-serif;
		font-size: 2em;
		background: rgba(0, 0, 0, 0.05);
	}
</style>
