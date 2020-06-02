<template>
  <div class="hello-world">
    <el-container style="height: 500px; border: 1px solid #eee">
      <my-aside></my-aside>
      <el-container direction="vertical">
        <my-header></my-header>
        <my-main></my-main>
      </el-container>
    </el-container>
  </div>
</template>

<script>
  import MyHeader from './MyHeader.vue'
  import MyAside from './MyAside.vue'
  import MyMain from './MyMain.vue'
  export default {
    name: 'HelloWorld',
    components: { MyAside, MyHeader, MyMain }
  }
</script>

<style lang="css" scoped>
</style>
