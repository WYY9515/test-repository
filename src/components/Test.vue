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
      console.log('测试git消息提交')
    }
  }
}
</script>
<style scoped>

</style>
