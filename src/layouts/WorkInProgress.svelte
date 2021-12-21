<script>
    export let name;
    export let color;
    import Card from '../components/Card.svelte';
</script>

  <svelte:head>
    <title>{name}</title>
  </svelte:head>

<body>
  <div>
  <Card> 
      <b style="color:{color}">{name}</b> is coming soon!
  </Card>
  </div>
</body>

<style>
  div {
    text-align : center;
    padding-top: 50vh;
    font-size: 100px;
  }
  
</style>