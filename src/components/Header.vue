<template>
  {{counter}}
  <button @click="this.counter++">Increment</button>
</template>

<script>
import { ref } from 'vue'
export default {
    name:"Header",
    setup(){
        const counter = ref(0)
        return {
            counter
        }
    },
    mounted() {
      alert("Funcionando")  
    },
}
</script>

<style>

</style>