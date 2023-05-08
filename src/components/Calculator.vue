<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>
<script>
export default{
  name: 'Calculator',
  props:{
    msg: String
  }
}

</script>




<template>
  <h1>{{ msg }}</h1>

  Hello World
</template>

<style scoped>

</style>
