<script>
  import List from "./List.svelte";

  export let item;
</script>

<li>
  {item.title}
  <List items={item.items}/>
</li>