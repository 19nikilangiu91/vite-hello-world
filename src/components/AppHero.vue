<script>
export default {
    data() {
        return {
            image: 'https://www.industrialempathy.com/img/remote/ZiClJf-1280w.avif',
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