<script lang="ts">
  import Repo from "$lib/repo.svelte"
</script>

<div>
  <Repo name="m" desc="Music.app CLI" url="https://github.com/thomascpowell/m"/>
  <Repo name="lift" desc="Workout tracker" url="https://github.com/thomascpowell/lift"/>
  <Repo name="pomo" desc="Pomodoro timer" url="https://pomo.thomas.loan"/>
</div>

<style>
  div {
    display: flex;
    justify-content: center;
    flex-direction: column;
    gap: 0.5em;
    max-width: 100%;
    overflow: scroll;
  }
</style>
