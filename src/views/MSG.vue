<template>
  <div class="info">
    <h1>This is an MSG page</h1>
     <Info msg="this is info component"/>
  </div>
</template>
<script>
// @ is an alias to /src
import Info from '@/components/Info.vue'
export default {
  name: 'Msg',
  components: {
    Info
  }
}
</script>
