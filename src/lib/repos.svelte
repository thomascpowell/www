<script lang="ts">
  import Repo from "$lib/repo.svelte"
</script>

<div>
  <h2>Featured<span></span></h2>
  <Repo name="m" desc="Music.app TUI remote" url="https://github.com/thomascpowell/m"/>
  <Repo name="drive" desc="Selfhosted file storage" url="https://github.com/thomascpowell/drive"/>
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
    transform: translateY(0.08em);
  }
</style>
