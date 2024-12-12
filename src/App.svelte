<script lang="ts">
  import Router from "svelte-spa-router";
  import routes from "./lib/routes";
  import "pattern.css/dist/pattern.min.css";
</script>

<div
  class="min-h-screen flex flex-col items-center justify-center bg-[#11111A] pattern-cross-dots-xl text-black"
>
  <Router {routes} />
</div>
