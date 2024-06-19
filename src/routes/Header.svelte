<script>
	import Button from '$lib/components/ui/button/button.svelte';
</script>

<nav class="navbar navbar-light">
	<div class="flex flex-row items-center justify-center gap-60 py-10">
		<h1 class="text-3xl font-semibold">TERRI</h1>
		<div class="flex space-x-20">
			<Button variant="link"><span class="text-xl font-bold">Marketplace</span></Button>
			<Button variant="link"><span class="text-xl font-bold">How It Works</span></Button>
			<Button variant="link"><span class="text-xl font-bold">Pricing</span></Button>
		</div>
		<div>
			<Button href="/login" variant="link"><b>Login</b></Button>
			<Button href="/register">Get Started</Button>
		</div>
	</div>
</nav>
