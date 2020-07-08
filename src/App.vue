<template>
  <div class="w-75 mx-auto mt-5">
    <b-card-group deck>
      <b-card no-body>
        <h1 class="m-3">Icebox</h1>
        <b-list-group class="m-3">
          <b-list-group-item>Test</b-list-group-item>
        </b-list-group>
      </b-card>

      <b-card no-body>
        <h1 class="m-3">In progress</h1>
        <b-list-group class="m-3">
          <b-list-group-item>In progress</b-list-group-item>
        </b-list-group>
      </b-card>

      <b-card no-body>
        <h1 class="m-3">Done</h1>
        <b-list-group class="m-3">
          <b-list-group-item>Done</b-list-group-item>
        </b-list-group>
      </b-card>

    </b-card-group>
  </div>
</template>

<script>
import Card from './Card.vue'

export default {
  name: 'app',
  components: {
    'app-card': Card
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

h1, h2 {
  font-weight: normal;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
