<script>
  export let name;
</script>

<main>
  <h1>Hello {name}!</h1>
  <p>
    Visit <a href="https://www.nba.com">NBA</a> to see who is in the Playoff right
    now.
  </p>
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: #001eff;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>
