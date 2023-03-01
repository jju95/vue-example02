<template>
  <div>
    <input type="text" v-model="userId"/> <br>
    <button @click="myFunction">alert</button>
    <button @click="changeData">변경</button>
</div>
</template>
<script>
export default {
  components: {},
  data() {
    return {
      userId: 'test'
    }
  },
  setup() {},
  created() {},
  mounted() {},
  unmounted() {},
  methods: {
    myFunction() {
      alert(this.userId)
    },
    changeData() {
      this.userId = '한글 테스트'
    }
  }
}
</script>

<style>

</style>
