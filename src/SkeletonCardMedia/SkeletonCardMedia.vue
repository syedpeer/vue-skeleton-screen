<template>
<v-card-media class='card-skeleton-media' :style="{height:height,width:width}"></v-card-media>
</template>

<script>

export default {
    name: "",
    props:['height','width']
}
</script>

<style scoped>

.card-skeleton-media{
    background-color: grey;
    height: 200px;
    width: auto;
}

</style>