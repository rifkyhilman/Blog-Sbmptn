<script>
  import Jumbotron from "../components/jumbotron.svelte";
  import Cards from "../components/cards.svelte";
</script>

<style>
  @media (min-width: 640px) {
    .body {
      max-width: none;
    }
  }

  .bodycar {
    margin-bottom: 10%;
  }
</style>

<div class="body">
  <div>
    <Jumbotron />
  </div>
  <div class="bodycar">
    <Cards />
  </div>
</div>
