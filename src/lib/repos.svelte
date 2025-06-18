<script lang="ts">
  import Repo from "$lib/repo.svelte"
</script>


<div>
  <h2>Projects<span></span></h2>
  <Repo name="m" desc="Music.app CLI" url="https://github.com/thomascpowell/m"/>
  <Repo name="lift" desc="Workout tracker" url="https://github.com/thomascpowell/lift"/>
  <Repo name="tomato" desc="Pomodoro timer" url="https://pomo.thomas.loan"/>
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
  h2 {
    display: flex;
    gap: 1em;
    align-items:center;
    width: 100%;
  }
  span {
    flex-grow: 1;
    border-bottom: .08em solid var(--text2);
    transform: translateY(0.08em);
  }
</style>
