<template lang="html">
  <div>
    <input type="text" v-model="message">
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data(){
    return{
      message: ''
    }
  }
}
</script>

<style lang="scss">
</style>
