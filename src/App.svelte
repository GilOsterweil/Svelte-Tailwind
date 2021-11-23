<script>
  import PlayerDetails from "./PlayerDetails.svelte";
  import Notes from "./Notes.svelte";
</script>

<div class="text-gray-700 flex bg-gray-500"><!-- content wrapper -->
  <div class="w-auto">
    <PlayerDetails />    
    <Notes/>
  </div>
  <div class="playbook w-2/3 bg-gray-400">MAIN</div>
  <div class="w-1/3 bg-gray-600">
    <div class="skills">HEADER</div>
    <div class="items"></div>
  </div>
</div>

<style lang="postcss" global>
  @tailwind base;
  @tailwind components;
  @tailwind utilities;  
</style>
