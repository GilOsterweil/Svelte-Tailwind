<form class="w-full max-w-sm p-4 space-x-1 space-y-3">    
    <img 
        src="https://www.burobrasil.com/blades-in-the-dark-srd/wp-content/uploads/2018/03/Blades-marca_preview-2.png" 
        alt="Blades In the Dark" class="w-full"/>    
    <input id="crew" type="text"/>
    <label for="crew">Crew</label>
    <input id="name" type="text"/>
    <label for="name">Name</label>
    <input id="alias" type="text"/>
    <label for="alias">Alias</label>
    <input id="look" type="text"/>
    <label for="look">Look</label>    
</form>

<style>
    label {
        @apply block tracking-wide text-gray-700 text-xs font-bold mb-2;
    }
    input {
        @apply appearance-none block w-full bg-gray-200 text-gray-700 border border-gray-200 rounded py-3 px-4 leading-tight;
    }    
</style>
