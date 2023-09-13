<script lang="ts">
    import { clipboard } from '@skeletonlabs/skeleton';

    const string: string = "never gonna give you up";
</script>


<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<button use:clipboard={string}>Copy</button>
