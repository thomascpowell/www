<script lang="ts">
  export let name: string = "";
  export let desc: string = "";
  export let url: string = "";
</script>

<div>
  <a target="_blank" rel="noopener noreferrer" href={url}>--> {desc}</a>
  <p>{name}</p>
</div>

<style>
  div {
    display: flex;
    gap: 1em;
    align-items: center;
    justify-content: space-between;
  }
  p {
    color: var(--text2);
    font-size: 1em;
  }

  a {
    color: var(--text2);
    font-size: 1em;
    cursor: pointer;
    width: min-content;
    white-space: nowrap;
    text-decoration: none;
    /* text-decoration-thickness: .08em; */
    text-decoration-color: var(--text);
    transition: 
      text-decoration-color .2s ease-in-out,
      color .3s ease-in-out;
  }
  a:hover {
    color: var(--text);
  }
</style>
