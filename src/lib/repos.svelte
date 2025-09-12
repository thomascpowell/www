<script lang="ts">
  import Repo from "$lib/repo.svelte"
</script>

<div>
  <h2>Projects<span></span></h2>
  <Repo name="drive" desc="Selfhosted file storage" url="https://github.com/thomascpowell/drive"/>
  <Repo name="redis" desc="Redis-like database" url="https://github.com/thomascpowell/redis"/>
  <Repo name="m" desc="Music.app TUI" url="https://github.com/thomascpowell/music-tui"/>
</div>

<style>
  div {
    display: flex;
    justify-content: center;
    flex-direction: column;
    gap: 0.5em;
    max-width: 100%;
  }
  h2 {
    display: flex;
    gap: 1em;
    align-items:center;
    width: 100%;
  }
  span {
    flex-grow: 1;
    border-bottom: .1em solid var(--border);
  }
</style>
