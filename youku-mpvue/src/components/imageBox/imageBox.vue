<template>
    <div class="image-box" :style="{width: imgWidth+'px', height: imgHeight +'px', borderRadius: imgRadius+'px',
    background: imgColor }">
        <img :src="imageUrl" alt="" class="box-pic">
    </div>
</template>

<script>
export default {

}
</script>

<style lang="stylus" scoped>
    .image-box
        padding 10%
        .box-pic
            width 100%
            height 100%
</style>
