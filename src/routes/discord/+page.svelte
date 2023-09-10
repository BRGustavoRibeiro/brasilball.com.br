<script>
	import Icon from '@iconify/svelte';
</script>

<div class="text-sm breadcrumbs not-prose">
	<ul>
		<li><a href="/">Início</a></li>
		<li>Discord</li>
	</ul>
</div>

<div class="form-control w-full max-w-xs">
	<label class="label justify-center" for="founders-nickname">
		<span class="label-text text-2xl font-bold">Qual é o apelido do fundador da IBB?</span>
	</label>
	<input type="text" name="founders-nickname" class="input input-bordered w-full max-w-xs" />
	<button class="btn btn-neutral text-white mt-3">
		<Icon icon="fa6-brands:discord" class="mr-2" />
		Entrar
	</button>
</div>
