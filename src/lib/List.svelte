<script>
  import Item from './Item.svelte';

  export let items = []
</script>

<ul>
  {#each items as item }
    <Item {item}/>
  {/each}
</ul>