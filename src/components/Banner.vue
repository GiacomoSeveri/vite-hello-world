<script>
import { assert } from '@vue/compiler-core';

export default {
    name: 'AppBanner',
    data() {
        return {
            image: 'BannerDBZ.jpeg'
        }
    },
    methods: {
        buildImg(image) {
            const url = new URL(`../assets/${image}`, import.meta.url);
            return url.href;
        }
    }
}
</script>

<template>
    <img :src="buildImg(image)" alt="se sei contrario sei un depensante">
</template>

<style scoped>
img {
    width: 850px;
}
</style>