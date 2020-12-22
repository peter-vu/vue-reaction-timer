<template>
  <div class="results">
      <p>Reaction time: {{score}} ms</p>
  </div>
</template>

<script>
export default {
    name: 'Results',
    props: ['score'],
    data() {
        return {
            // reactionTime: null
        }
    }
}
</script>

<style>

</style>