<template>
  <a-layout>
    <!--  顶部  -->
    <the-header />

    <router-view />

    <!--  底部  -->
    <the-footer />
  </a-layout>
</template>

<script setup lang="ts">
import TheHeader from '@/components/the-header.vue'
import TheFooter from '@/components/the-footer.vue'
</script>

<style lang="scss"></style>
