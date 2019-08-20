<template>
  <div>
    <h1></h1>
    <div></div>
    <div>
      <ul>
        <li v-for="item in theThing1">{{ item }}</li>
      </ul>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      theThing1: ['blabla', 'altceva']
    }
  }
}
</script>

<style>
</style>