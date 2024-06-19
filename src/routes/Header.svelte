<script>
	import Button from '$lib/components/ui/button/button.svelte';
	import Icon from '@iconify/svelte';
</script>

<nav class="navbar navbar-light">
	<div class="flex flex-row items-center justify-center gap-60 py-10">
		<div class="flex flex-row items-center space-x-2">
			<Icon class="h-12 w-12" icon="fluent:animal-cat-24-regular"  />
			<span class="text-3xl underline font-semibold">terri</span>
		</div>
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
