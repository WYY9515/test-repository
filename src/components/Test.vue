<template>
    <div @click="change">
        {{val}}
    </div>
</template>
<script>
export default {
  data () {
    return {
      val: 'great'
    }
  },
  methods: {
    change () {
      console.log(this.val)
      console.log(111)
    }
  }
}
</script>
<style scoped>

</style>
