<script lang="ts">
    export let identifier: String;

    function getIdentifier(): String {
        return identifier.toUpperCase();
    }

</script>

<style>
    .identifier {
        background-color: #309186;
        color: black;
        font-size: 15px;
        font-weight: 500;
        padding: 0 5px;
    }
</style>

<template>
    <span class="identifier">{ getIdentifier() }</span>
</template>