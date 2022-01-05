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

  @media (max-width: 790px) {
		div {
			font-size: 65px;
		}
	}

  @media (max-width: 690px) {
		div {
			font-size: 50px;
		}
	}

  @media (max-width: 530px) {
		div {
			font-size: 35px;
		}
	}

  @media (max-width: 370px) {
		div {
			font-size: 25px;
		}
	}
</style>