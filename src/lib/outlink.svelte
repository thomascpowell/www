<script lang="ts">
  export let href: string;
  export let text: string;
</script>

<a class="outlink" href={href} target="_blank" rel="noopener noreferrer">
  {text} 
  <svg  xmlns="http://www.w3.org/2000/svg"  width="20"  height="20"  viewBox="0 0 24 24"  fill="none"  stroke="currentColor"  stroke-width="2"  stroke-linecap="round"  stroke-linejoin="round"  class="icon icon-tabler icons-tabler-outline icon-tabler-arrow-narrow-right"><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M5 12l14 0" /><path d="M15 16l4 -4"/><path d="M15 8l4 4" /></svg>
</a>

<style>
  a {
    color: var(--text2);
    text-decoration: none;
    display: flex;
    align-items: center;
    gap: .1em;
  }
  a svg {
    transition: transform 0.2s ease;
  }
  a:hover svg {
    transform: translateX(1px);
  }
</style>
