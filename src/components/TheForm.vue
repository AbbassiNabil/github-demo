<template>
  <header class="text-center">
    <h1>The Form</h1>
  </header>
  <section>
    <v-form>
      <!-- <input type="button">
           <input type="checkbox">
           <input type="color">
           <input type="date">
           <input type="datetime-local">
           <input type="email">
           <input type="file">
           <input type="hidden">
           <input type="image">
           <input type="month">
           <input type="number">
           <input type="password">
           <input type="radio">
           <input type="range">
           <input type="reset">
           <input type="search">
           <input type="submit">
           <input type="tel">
           <input type="text">
           <input type="time">
           <input type="url">
           <input type="week"> -->
    </v-form>
  </section>
  <v-snackbar
    v-model="snackbarVisibility"
    :color="snackbarColor"
    :timeout=1000
  >
    <div class="text-center">{{ snackbarText }}</div>
  </v-snackbar>
</template>

<script setup lang="ts">
  let snackbarColor = '';
  let snackbarVisibility = false;
  let snackbarText = '';

  function checkResult() {
  }
</script>

<style scoped>

</style>
