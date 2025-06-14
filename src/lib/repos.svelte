<script lang="ts">
  import Repo from "$lib/repo.svelte"
</script>

<div>
  <h1>Projects</h1>
    <Repo name="m" desc="CLI music controller" url="https://github.com/thomascpowell/m"/>
    <Repo name="lift" desc="Workout tracker" url="https://github.com/thomascpowell/lift"/>
    <Repo name="pomo" desc="Pomodoro timer" url="pomo.pwl.red"/>
</div>

<style>
  div {
    margin-top: 2em;
    display: flex;
    justify-content: center;
    flex-direction: column;
    gap: 0.5em;
    max-width: 100%;
    overflow: scroll;
  }
  h1 {
    font-size: 1.2em
  }
</style>
