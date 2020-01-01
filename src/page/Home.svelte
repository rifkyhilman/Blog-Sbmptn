<script>
  import Carousel from "../components/carousel.svelte";
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
  <Carousel />
  <div class="m-5">
    <Cards />
  </div>
</div>
