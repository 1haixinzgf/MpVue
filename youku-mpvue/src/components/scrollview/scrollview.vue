<template>
    <scroll-view :scroll-x="true" class="header-nav" :style="{width: scroll-width + 'px'}">
        <ul>
            <li class="nav-item" :class="{'active': changeNav == item.index}"
             v-for="(item,index) in navs" :key="index" :data-nav="item.index">
             <span class="nav-text">{{item}}</span></li>
        </ul>

    </scroll-view>
</template>

<script>
export default {
    data() {
        return {
            navs: ["精选","世界杯","夜现场","看点","剧集","综艺","少儿","电影","直播"]
        }
    }
}
</script>

<style lang="stylus" scoped>
   

</style>
