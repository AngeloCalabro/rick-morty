<template>
    <div class="character">
        <img :src="character.image" :alt="character.name">
        <h2>{{ character.name }}</h2>
        <h3>{{ character.status }}</h3>
        <h3>{{ character.species }}</h3>
    </div>
</template>

<script>
    export default {
        name: 'CardComponent',
        props: {
            character: Object
        }
    }
</script>

<style lang="scss" scoped>

</style>