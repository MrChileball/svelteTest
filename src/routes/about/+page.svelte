<script>
    import Nested from '../Nested.svelte';
    
    /*import { onMount } from 'svelte';

    onMount(() => {

    setTimeout(() => {
        const styleBody = document.body;
        styleBody.classList.add('fade-in-nonlinear');
        styleBody.style.visibility = 'visible';
    }, 1000);

    });*/
	let count = 0;

	function handleClick() {
		count += 1;
	}
</script>

<svelte:head>
	<title>About</title>
	<meta name="description" content="About this app" />
</svelte:head>
<button on:click={handleClick}>
	Clicked {count}
	{count === 1 ? 'time' : 'times'}
</button>



<h1>Welcome to SveKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<p>These styles...</p>


