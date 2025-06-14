<script lang="ts">
  export let name: string = "";
  export let desc: string = "";
  export let url: string = "";
</script>

<div>
  <p>{name}</p>
  <a target="_blank" rel="noopener noreferrer" href={url}>{desc}</a>
</div>

<style>
  div {
    display: flex;
    align-items: center;
  }
  p {
    min-width: 5em;
    padding-right: 1em;
    color: var(--text2);
    font-size: 1em;
  }
  a {
    font-size: 1em;
    cursor: pointer;
    color: var(--text);
    width: min-content;
    white-space: nowrap;
    text-decoration: underline;
    text-decoration-thickness: .05em;
    text-decoration-color: var(--text2);
    transition: text-decoration-color .25s ease-in-out;
  }
  a:hover {
    text-decoration-color: transparent;
  }
</style>
