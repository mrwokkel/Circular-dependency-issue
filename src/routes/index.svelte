<script>
	import List from '../lib/List.svelte';
  const items = [
    {
      title: 'election'
    },
    {
      title: 'lot'
    },
    {
      title: 'embody',
      items: [
        {
          title: 'contain'
        },
        {
          title: 'praise',
          items: [
            {
              title: 'stimulate'
            },
            {
              title: 'complain'
            }
          ]
        }
      ]
    },
    {
      title: 'reserve'
    },
    {
      title: 'suffer',
      items: [
        {
          title: 'complain'
        },
        {
          title: 'answer',
          items: [
            {
              title: 'compensate'
            }
          ]
        },
        {
          title: 'criticize'
        },
        {
          title: 'highlight'
        }
      ]
    },
    {
      title: 'greedy'
    }
  ]
</script>

<main>
	<List {items} />
</main>

<style>
	:root {
		font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell,
			'Open Sans', 'Helvetica Neue', sans-serif;
	}
</style>
