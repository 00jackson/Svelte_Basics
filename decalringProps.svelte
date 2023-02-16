//we need to declare properties, generally shortened to 'props'. In Svelte, we do that with the export keyword. Edit the Nested.svelte component:

<script>
	export let answer;
</script>
//

<script>
	import Nested from './Nested.svelte';
</script>

<Nested answer={42}/>

