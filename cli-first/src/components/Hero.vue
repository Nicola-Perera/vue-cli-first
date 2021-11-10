<template>
  <div class="jumbotron">
    <h1>{{ hero }}</h1>
    </div>
</template>

<script>
export default {
  name: 'Hero',
  props: {
    hero: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>

</style>