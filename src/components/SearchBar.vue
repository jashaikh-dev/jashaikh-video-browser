<template>
    <div> 
        <input @input = "onInput" type="text" name="search-bar" id="searchBar">
    </div>
</template>

<script>
    export default {
        name: 'SearchBar'
    }
</script>

<style>
    #searchBar{
        height: 40px;
        width: 50%;
        border-radius: 5px;
        font-size: 14px;
        border: 1px solid #ddd;
        padding: 10px
    }
</style>