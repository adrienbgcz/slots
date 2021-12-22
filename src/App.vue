<template>
  <div id="app">
    <Card>
      <h2>Subtitle</h2>
      <p>texte</p>
    </Card>
    <Card>
      <button>oui</button>
    </Card>
  </div>
</template>

<script>
import Card from "./components/Card.vue"

export default {
  name: 'App',
  components: {
    Card
  }
}
</script>

<style>

</style>
