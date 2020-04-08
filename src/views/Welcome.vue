<template>
  <div id="welcome">
    <h3>Welcome,My Friend!</h3>
    <router-link to="/home">
      <h3>go home~</h3>
    </router-link>
  </div>
</template>
<script>
export default {
  name: 'Welcome',
  data() {
    return {}
  },
  components: {},
  created() {},
  mounted() {},
  methods: {},
  computed: {}
}
</script>

<style lang="scss">
#welcome {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
