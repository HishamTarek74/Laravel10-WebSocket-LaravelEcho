

<template>
    <h1>
        How To Install Vue 3 in Laravel 10 : Laravel SPA :)
    </h1>
</template>

<script >
    export default {
        name: "Home Component",
        data() {
            return {}
        },

        mounted() {
            window.Echo.channel('SendMessageChannel').listen('SendMessage', event => {
                console.log(event);
            });
        },

    }
</script>
