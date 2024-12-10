<div class="portal">
	<slot />
</div>

<style>
	.portal :global{
		.main {
			display: flex;
			color: red;
		}
		p {
			color: green;
		}
	}
</style>
