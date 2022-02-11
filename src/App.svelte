<script>

</script>

<div class="container">
  <h1>Welcome</h1>
  <p>Starting a new project.</p>
</div>

<style>
  :global(:root) {
    --white: hsla(0, 100%, 100%, 1);
    --black: hsla(0, 0%, 0%, 1);
    --grey30: hsla(0, 0%, 30%, 1);
    --grey50: hsla(0, 0%, 50%, 1);
    --grey70: hsla(0, 0%, 70%, 1);
  }

  :global(body) {
    background-color: var(--grey70);
    font-size: 62.5% /* 10px */
  }

  .container {
    max-width: 120rem;
    margin: 0 auto;
  }

  @media (min-width: 64rem) {
    .container {
      max-width: none;
    }
  }
</style>
