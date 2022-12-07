<script>
export default {
    data() {
        return {
            image: 'https://mdbcdn.b-cdn.net/img/new/slides/041.webp',
        }
    }
}

</script>

<template>
    <div>
        <img :src="image">
    </div>
</template>

<style scoped>
div {
    width: 100%;
    height: 100%;
}
</style>