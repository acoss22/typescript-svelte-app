<script lang="ts">
	export let name: string = '';
	//export let max: number;
	//max+='s' you can't do this because it's ts now!
</script>

<style type='text/scss'>
	@import './styles/vars';
  
	h1 {
	  color: $color;
	  font-weight: 300;
	  font-size: 64px;
	}
  </style>


<h1>Hello {name}</h1>
<input type="text" bind:value={name}>

