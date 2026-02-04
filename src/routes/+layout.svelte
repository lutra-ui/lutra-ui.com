<script lang="ts">
	import icon from './icon.png';
	import './style.css';
	let { children } = $props();
</script>

<svelte:head>
	<link rel="icon" href={icon} />
</svelte:head>

<main>
	{@render children()}
</main>

<style> 
    main {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        height: 100vh;
        width: 100vw;
    }
</style>