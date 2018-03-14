<template>
  <div id="app" class="container">
    <MyForm></MyForm>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MyForm from './components/Form.vue'

export default {
  name: 'app',
  data: {
    first: 'aaa',
    last: 'bbb'
  },
  methods: {
    onSubmit: function (event) {
      alert('submiting');
    }
  },
  components: {
    HelloWorld,
    MyForm
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
