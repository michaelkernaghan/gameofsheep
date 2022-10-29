<script>
  import Counter from "./lib/Counter.svelte";
</script>

<main>
  <div>
    <img src="/GoS-transparent.png" width="300" alt="GoS Logo" />
  </div>
  <h1>Game of Sheep</h1>

  <div class="card">
    <Counter />
  </div>

</main>

<style>
  :global(body) {
    background-color: #aaaaa0;
  }
  h1 {
      color: black;
      font-family: "Luminari", fantasy;
      font-size: 80px;
      margin: 10px;
    }
</style>
