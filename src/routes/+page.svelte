<script lang="ts">
	import '$lib/default.css';
	import Icon from '@iconify/svelte';
</script>

<svelte:head>
	<title>Brasilball</title>
</svelte:head>

<h1>Brasilball</h1>

<div>
	<ul class="menu glass w-36 rounded-box">
		<li>
			<a href="/discord" class="flex justify-between w-full font-bold">
				<Icon icon="fa6-brands:discord" width={25} />
				Discord
			</a>
		</li>
		<li>
			<a href="/acervo" class="flex justify-between w-full font-bold">
				<Icon icon="fa6-solid:box-archive" width={25} />
				Acervo
			</a>
		</li>
		<li>
			<a href="/contato" class="flex justify-between w-full font-bold">
				<Icon icon="fa6-solid:envelope" width={22} />
				Contato
			</a>
		</li>
	</ul>
</div>

<p>
	<small>
		Em um momento futuro, será disponibilizado o BallAtlas, um mapa interativo desenvolvido desde
		2019, com conteúdos de países e suas balls.
	</small>
</p>
