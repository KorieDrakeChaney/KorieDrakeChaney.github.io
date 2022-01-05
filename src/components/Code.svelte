<script>
    let text = '';
</script>



<span contenteditable="true" bind:textContent={text} class="hide">
    <slot/>
</span>

{text}


<style>
    .hide { 
        display : none;
    }
</style>