<template>
  <div class="container" id="app">
      <router-view></router-view>
    </div>
</template>

<script>
export default {
  methods: {
  mounted() {
  this.$store.dispatch("doReadStateFromStorage")
    }
  }
}
</script>