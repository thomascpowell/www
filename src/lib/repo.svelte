<script lang="ts">
  export let name: string = "";
  export let desc: string = "";
  export let url: string = "";
</script>

<a href={url} target="_blank" rel="noopener noreferrer">
  <p >{desc}</p>
  <p>--></p>
</a>

<style>
  a {
    display: flex;
    gap: 1em;
    align-items: center;
    text-decoration: none;
    justify-content: space-between;
  }
  p {
    color: var(--text2);
    font-size: 1em;
    cursor: pointer;
    width: min-content;
    white-space: nowrap;
    transition: color 0.3s ease;
  }
  a:hover > p {
    color: var(--text);
  }
</style>
