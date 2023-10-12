<script>
    import '../styles.css';
    import Navbar from './Navbar.svelte';

</script>

<!--  EL SLOT PERMITE INSERTAR EL RESTO DEL CONTENIDO DENTRO DE LA PÁGINA AL CARGAR-->
<div class="app">

<Navbar />
	<main>
		<slot />
	</main>

	<footer>
		<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
	</footer>
</div>
