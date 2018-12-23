<template>
  <svg v-if="name" class="icons">
    <use :xlink:href="`#i-${name}`"></use>
  </svg>
</template>
<script>
export default {
  props:['name']
}
</script>
<style lang="scss" scoped>
.icons {width:1em;height:1em}
</style>