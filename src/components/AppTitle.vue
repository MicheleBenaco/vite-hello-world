<template>
    <div>
        <h1>{{titolo}}</h1>
    </div>
</template>

<script>
    export default {
        name:'AppTitle',
        name: 'AppHero',
        data() {
            return {
                titolo:'La mia prima app con Vite!'
            }
        },
        
    }
</script>

<style lang="css" >
    h1{
        color: red;

    }
</style>