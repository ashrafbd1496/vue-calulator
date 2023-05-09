<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
  name: 'Calculator',
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
  <div class="calcualator p-3 max-w-md m-12 mx-auto bg-cyan-700">
    <!-- calculator result -->
    <div class="result w-full rounded m-1 p-3 text-right leading-3 font-bold text-white">
     0
    </div>
    
  </div>

</template>

<style scoped>

</style>
