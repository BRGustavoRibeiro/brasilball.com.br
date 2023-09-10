<script lang="ts">
	import '@fontsource/aileron/400.css';
	import '@fontsource/aileron/600.css';
	import '@fontsource/aileron/700.css';
	import '@fontsource/aileron/800.css';
	import '$lib/default.css';
</script>

<div class="w-[100vw] h-[100vh] bg-gradient-to-br from-blue-100 to-green-200">
	<div class="container prose flex text-center justify-center items-center flex-col h-[100vh]">
		<slot />
	</div>
</div>
