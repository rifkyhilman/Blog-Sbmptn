<script>
  import Navbar from "../components/navbar.svelte";
  import Jumbotron from "../components/jumbotron.svelte";
  import Cards from "../components/cards.svelte";
</script>

<style>
  @media (min-width: 640px) {
    .body {
      max-width: none;
    }
  }
</style>

<div class="body">
  <Navbar />
  <Jumbotron />
  <Cards />
</div>
