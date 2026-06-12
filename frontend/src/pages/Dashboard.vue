<template>
  <div class="dashboard">
    <div class="container mx-auto px-4 py-8">
      <h1 class="text-3xl font-bold mb-6">Bienvenido a Assetium</h1>
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <div class="bg-white p-6 rounded-lg shadow">
          <h2 class="text-xl font-semibold mb-2">Equipos</h2>
          <p class="text-gray-600">Gestiona tus equipos de forma eficiente</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow">
          <h2 class="text-xl font-semibold mb-2">Usuarios</h2>
          <p class="text-gray-600">Administra los usuarios del sistema</p>
        </div>
        <div class="bg-white p-6 rounded-lg shadow">
          <h2 class="text-xl font-semibold mb-2">Reportes</h2>
          <p class="text-gray-600">Visualiza reportes y análisis</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Dashboard',
  data() {
    return {}
  },
  mounted() {
    console.log('Dashboard cargado')
  }
}
</script>

<style scoped>
.dashboard {
  width: 100%;
  min-height: 100vh;
  background-color: #f8fafc;
}
</style>
