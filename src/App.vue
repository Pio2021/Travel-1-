<template>
  <div id="app">
    <keep-alive exclude="Detail">    <!-- exclude 在这里是不被缓存，后面是组件名字 -->
      <router-view/>
    </keep-alive>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>

</style>
