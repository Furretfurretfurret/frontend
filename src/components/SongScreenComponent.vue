<template>
  <div class="hello">
    <p>
      The song is called {{songid}}
    </p>
  </div>
</template>

<script>
export default {
  name: 'SongScreenComponent',
  props: ['songid'],
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
