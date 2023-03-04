<script>
  import { fade } from "svelte/transition";
</script>

<div>
    <h2>APP PAGE</h2>
    <a href="/">Goto Home</a>
    <!-- this transition causes the app page to not be removed -->
    <div transition:fade>This uses transition</div>
</div>