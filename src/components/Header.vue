<template>
  <header>
    <h1>{{title}}</h1>
    <Button color="green" text="Add TasK"/>
  </header>
</template>

<script>
  import Button from './Button';

  export default {
    name: 'Header',
    components: {
      Button
    },
    props: {
      title: {
        type: String,
        default: "Helllo",
      }
    }
  }
</script>

<style scoped>
  header {
    display: flex;
    justify-content: space-between;
    align-content: center;
    margin-bottom: 20px;
  }
</style>