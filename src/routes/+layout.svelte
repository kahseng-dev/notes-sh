<script lang="ts">
  import "../app.css";
  import "../light.theme.css";

  import Sidebar from "$lib/components/Sidebar.svelte";
</script>

<main
  class="grid grid-flow-col grid-cols-12 h-screen p-1 gap-1 antialiased text-pretty tracking-tight bg-[var(--bg-0)]"
>
  <Sidebar />
  <slot />
</main>
