<template>
    <button class="g-button">button</button>
</template>
<script>
    export default {}

</script>
<style>
    .g-button {
        font-size: var(--font-size);
        height: var(--button-height);
        padding:0 1em;   /* width not fixed*/
        border-radius: var(--border-radius);
        border: 1px solid var(--border-color);
        background: var(--button-bg);
    }
    .g-button:hover{
        border-color: var(--border-color-hover);
    }
    .g-button:active{
        background-color: var(--button-active-bg);
    }
    .g-button:focus{
        outline: none;
    }
</style>