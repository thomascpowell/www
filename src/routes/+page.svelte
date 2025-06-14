<script>
  import Repos from '$lib/repos.svelte';
  import Outlink from "$lib/outlink.svelte"
</script>

<div class="header">
  <h1>Thomas Powell</h1>
  <p>
    I'm a student learning CS and SWE. Senior at UNCW.
  </p>
  <div class="links">
    <Outlink href="https://github.com/thomascpowell" text="Github"/>
    <Outlink href="mailto:thomascoxpowell@gmail.com" text="Email"/>
  </div>
</div>

<Repos/>

<style>
  .header {
    display: flex;
    flex-direction: column;
    gap: 0.5em;
  }
  .links {
    display: flex;
    gap: 1em;
  }
  h1 {
    font-size: 1.2em;
  }
  p {
    color: var(--text2)
  }
</style>
