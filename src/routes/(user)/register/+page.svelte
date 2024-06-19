<script>
	import Button from '$lib/components/ui/button/button.svelte';
	import Input from '$lib/components/ui/input/input.svelte';
	import Icon from '@iconify/svelte';
</script>

<div class="flex flex-col items-center py-96">
	<div class="flex flex-col items-center space-y-4">
		<p class="text-2xl font-bold">Create An Account</p>
		<p class="text-sm">Enter your email below to create your account</p>
	</div>
	<div class="flex w-96 flex-col items-center space-y-2 pt-5">
		<Input type="email" placeholder="Email" />
		<Button class="w-full">Register With Email</Button>
	</div>
	<div class="inline-flex w-full items-center justify-center">
		<hr class="my-8 h-px w-64 border-0 bg-gray-200 dark:bg-gray-700" />
		<span
			class="absolute left-1/2 -translate-x-1/2 bg-white px-3 font-medium text-gray-900 dark:bg-gray-900 dark:text-white"
			>OR REGISTER WITH</span
		>
	</div>
	<div class="flex w-96 flex-col items-center space-y-2">
		<Button class="w-full">
			<Icon icon="flat-color-icons:google" class="mr-3 h-6 w-6" />
			Register With Google
		</Button>
	</div>
	<span class="inline-block w-72 pt-5 text-sm"
		>By clicking continue, you agree with our <u>Terms of Service</u> and
		<u>Privacy Policy.</u></span
	>
</div>
