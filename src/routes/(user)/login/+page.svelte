<script>
	import Button from '$lib/components/ui/button/button.svelte';
	import Checkbox from '$lib/components/ui/checkbox/checkbox.svelte';
	import Input from '$lib/components/ui/input/input.svelte';
	import Label from '$lib/components/ui/label/label.svelte';
	import Icon from '@iconify/svelte';
</script>

<div class="flex flex-col items-center py-96">
	<div class="flex flex-col items-center space-y-4">
		<p class="text-2xl font-bold">Login To Your Account</p>
		<p class="text-sm">Enter your email and password below to login</p>
	</div>
	<div class="flex w-96 flex-col items-center space-y-2 pt-5">
		<Input type="email" placeholder="Email" />
		<Input type="password" placeholder="Password" />
		<div class="flex w-full items-center space-x-2">
			<Checkbox />
			<Label for="remember-me" class="my-3 text-xs">Remember me</Label>
		</div>
		<Button class="w-full">Login</Button>
	</div>
	<div class="inline-flex w-full items-center justify-center">
		<hr class="my-8 h-px w-64 border-0 bg-gray-200 dark:bg-gray-700" />
		<span
			class="absolute left-1/2 -translate-x-1/2 bg-white px-3 font-medium text-gray-900 dark:bg-gray-900 dark:text-white"
			>OR LOGIN WITH</span
		>
	</div>
	<div class="flex w-96 flex-col items-center space-y-2">
		<Button class="w-full">
			<Icon icon="flat-color-icons:google" class="mr-3 h-6 w-6" />
			Login With Google
		</Button>
	</div>
	<span class="inline-block w-72 pt-5 text-sm"
		>By clicking continue, you agree with our <u>Terms of Service</u> and
		<u>Privacy Policy.</u></span
	>
</div>
