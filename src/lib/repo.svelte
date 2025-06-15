<script lang="ts">
  export let name: string = "";
  export let desc: string = "";
  export let url: string = "";
</script>

<div>
  <a target="_blank" rel="noopener noreferrer" href={url}>{desc}</a>
  <span></span>
  <p>"{name}"</p>
</div>

<style>
  div {
    display: flex;
    gap: 1em;
    align-items: center;
    justify-content: space-between;
  }
  p {
    /* min-width: 2em; */
    /* padding-right: 1em; */
    color: var(--text2);
    font-size: 1em;
  }
  span {
    flex-grow: 1;
    border-bottom: .08em solid var(--text2);
    transform: translateY(0.1em);
  }
  a {
    color: var(--text);
    font-size: 1em;
    cursor: pointer;
    width: min-content;
    white-space: nowrap;
    text-decoration: underline;
    text-decoration-thickness: .08em;
    text-decoration-color: var(--text);
    transition: 
      text-decoration-color .3s ease-in-out,
      color .3s ease-in-out;
  }
  a:hover {
    color: var(--text);
    text-decoration-color: transparent;
  }
</style>
