<script lang="ts">
	import Form from "$lib/components/Form.svelte";
    import Table from "$lib/components/Table.svelte";
	import type { PageData } from "./$types";

    export let data;

    console.log('data en /[tables]/+page.svelte', data);
    

</script>

<h2>Esta es una página en la ruta [tables] </h2>

<Table />

<Form />