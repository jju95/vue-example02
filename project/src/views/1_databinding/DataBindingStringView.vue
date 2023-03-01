<template>
    <div>
        <h1>Hello {{ userName }}</h1>
        <p>{{ message }}</p>
    </div>
</template>
<script>
export default {
  data() {
    return {
      userName: 'John Doe',
      message: 'Wellcome vue 실습~!',
      arr: [],
      obj: {}
    }
  }
}
</script>
<style scoped>
.text-red {
    color: red;
}
</style>
