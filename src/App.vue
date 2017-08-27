<template>
  <div id="app">
    <input type="text" v-model="nama"> {{ nama }}
    <pre>{{ $data | json}}</pre>
  </div>
</template>

<script>
export default {
  name: 'app',
  data() {
    return {
      nama: 'rosyid'
    }
  }
}
</script>

<style lang="scss">

</style>
