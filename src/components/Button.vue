<template>
  <button @click="onClick">
    <slot>ボタン</slot>
  </button>
</template>

<script>
export default {
  props:{
    onClick:{
      type:Function
    }
  }


}
</script>

<style>

</style>