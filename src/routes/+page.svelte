<script>
	import Button from '$lib/components/ui/button/button.svelte';
	import Icon from '@iconify/svelte';
	import Header from './Header.svelte';
	import Footer from './Footer.svelte';
</script>

<Header />
<main
	class="flex flex-col items-center space-y-20 bg-contain bg-[position:75%_0%] bg-no-repeat py-52"
	style="background-image: url('https://static.vecteezy.com/system/resources/previews/027/537/533/large_2x/snowshoe-cat-sitting-on-white-background-ai-generative-free-photo.jpeg');"
>
	<div class="flex flex-col items-center space-y-12">
		<p class="text-2xl font-semibold">Toronto's Referral Market</p>
		<p class="text-6xl font-bold"><u>Buy & Sell</u> Referrals For Leading Firms</p>
		<p>
			Secure an edge by connecting and collaborating with existing employees in roles you're
			interested in.
		</p>
		<Button
			><Icon icon="fluent-mdl2:market" class="mr-3 h-5 w-5" />
			<span class="text-xl">See Marketplace</span></Button
		>
	</div>
</main>
<Footer />
