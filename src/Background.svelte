<script>
    export let title = "Her"
    export let backgrounds = [
        "O1",
        "O2",
    ]
</script>

<div class="container flex gap-1">    
    <span class="text-xs">{title}</span>
    {#each backgrounds as background}
    <div>
        <input id="{background}" class="hidden" type="radio" name="{title}"/>        
        <label for="{background}" class="text-xs label-checked:bg-red-600">{background}</label>        
    </div>
    {/each}        
</div>

