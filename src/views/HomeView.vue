<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <h1>Hola mundo</h1>
    <button @click="gotoDayBook" class="btn btn-primary">Primary</button>
    <button @click="gotoDayBook" class="btn btn-secondary">Secondary</button>
    <button @click="gotoDayBook" class="btn btn-success">Success</button>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'HomeView',
  components: {
  },
  methods: {
    gotoDayBook() {
      this.$router.push({ name: 'no-entry' })
    }
  }

}
</script>
