<script lang="ts">
	export let name: string = '';
	//export let max: number;
	//max+='s' you can't do this because it's ts now!
</script>

<h1>Hello {name}</h1>
<input type="text" bind:value={name}>
