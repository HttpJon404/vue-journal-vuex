<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png" />
    <h1>Hola mundo</h1>
    <button @click="goToDayBook" class="btn btn-sm btn-primary">primary</button>
    <button @click="goToDayBook" class="btn btn-sm btn-secondary">secundario</button>
    <button @click="goToDayBook" class="btn btn-sm btn-success">success</button>
  </div>
</template>

<script>
export default {

  methods: {
    goToDayBook(){
      this.$router.push({name:'no-entry'})
    }
  },
};
</script>
