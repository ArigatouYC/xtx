<script setup>
import LayoutNav from './components/LayoutNav.vue'
import LayoutHeader from './components/LayoutHeader.vue'
import LayoutFooter from './components/LayoutFooter.vue'
import LayoutSticky from './components/LayoutSticky.vue'
</script>

<template>
    <LayoutNav />
    <LayoutSticky />
    <LayoutHeader />
    <RouterView />
    <LayoutFooter />
    <div class="s"></div>
</template>

<style lang="scss">
.s {
    height: 2000px;
}
</style>