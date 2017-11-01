<template>
  <div class="hello">
    <div class="test">
    {{msg}}:{{age}}
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      age:23
    }
  }
}
</script>


<style scoped>
.test{
	background:red;
}
</style>
