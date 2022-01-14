<template>
    <div class="thumb">
        <div class="img-container">
            <img :src="img" :alt="alt">
        </div>
        <span class="subtitle">{{title}}</span>
    </div>
</template>

<script>
export default {
    name: "Product",
    props: ["img", "alt", "title", "type", "price"],
    data(){
        return {
        }
    }
}
</script>

<style lang="scss" scoped>
.thumb {
    width: 150px;
    .img-container {
        height: 150px;
        width: 150px;
        overflow: hidden;
        margin-bottom: 1em;
        img {
            width: 100%;
        }
    }
    .subtitle {
        color: white;
        text-transform: uppercase;
        font-size: 0.8em;
    }
}
</style>