<script>
	import Button from '$lib/components/ui/button/button.svelte';
	import Separator from '$lib/components/ui/separator/separator.svelte';
</script>

<div class="flex flex-col gap-y-10 py-10">
	<Separator />
	<div class="flex flex-row items-center justify-center space-x-10">
		<b>© 2024 Terri Corp.</b>
		<Button variant="link"><u>About Us</u></Button>
		<Button variant="link"><u>Terms of Service</u></Button>
		<Button variant="link"><u>Privacy Policy</u></Button>
		<Button variant="link"><u>Cookie Policy</u></Button>
	</div>
</div>
