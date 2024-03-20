<script>

import secondapp from './components/secondapp.vue';

export default {
  components: {
    secondapp
  },
  data() {
    return {
      title: 'Hi here i am'
    }

  }
}
</script>

<template>
  <h1>{{ title }}</h1>
  <secondapp />
</template>

<style></style>
