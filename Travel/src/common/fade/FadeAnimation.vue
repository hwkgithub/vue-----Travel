<!--
 * @Description: 
 * @Autor: HWK
 * @Date: 2020-09-16 22:20:03
 * @LastEditors: HWK
 * @LastEditTime: 2020-09-28 15:21:30
-->
<template>
  <transition>
    <slot></slot>
  </transition>
</template>

<script>
export default {
  name: 'FadeAnimation',
}
</script>

<style lang="stylus" scoped>
.v-enter, .v-leave-to
  opacity 0
.v-enter-active, .v-leave-active
  transition opacity 0.5s
</style>
