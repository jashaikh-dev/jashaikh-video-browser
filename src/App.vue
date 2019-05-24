<template>
    <div>
        <SearchBar onInput="onInput"></SearchBar>
    </div>
</template>

<script>
    import SearchBar from './components/SearchBar';
    export default {
        name: 'App',
        components: {
            SearchBar
        },
        methods: {
            onInput: function (event) {
                console.log(event.target.value);
            }
        }
    }
</script>

