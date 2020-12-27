<template>
  <div class="info">
    <h1>{{ msg }}</h1>
    <span> this is div</span>
  </div>
</template>
<script>
export default {
  name: 'Info',
  props: {
    msg: String
  }
}
</script>
