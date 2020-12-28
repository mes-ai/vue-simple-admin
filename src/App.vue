<template>
  <div id="app">
<span>this is demo</span>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style >
span{
  text-align: center;
  display:block;
  background-color: cornflowerblue;
  font-size: 30px;
}
</style>
