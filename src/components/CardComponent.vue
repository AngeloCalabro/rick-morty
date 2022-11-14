<template>
    <div class="character">
        <img :src="item.image" :alt="item.name">
        <h2>{{ item.name }}</h2>
        <h3>{{ item.status }}</h3>
        <h3>{{ item.species }}</h3>
    </div>
</template>

<script>
    export default {
        name: 'CardComponet',
        props: {
            character: Object
        }
    }
</script>

<style lang="scss" scoped>

</style>