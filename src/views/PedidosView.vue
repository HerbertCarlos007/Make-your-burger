<template>
  <div class="main-container">
    <h1>Gerenciar pedidos:</h1>
    <Dashboard />
  </div>
</template>

<script>
import Dashboard from '../components/Dashboard.vue'

export default {
  name: 'PedidosView',

  components: {
    Dashboard
  }
}
</script>

<style scoped>
.main-container {
  margin: 50px;
  min-height: 600px;
}
</style>