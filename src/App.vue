<template>
  <section class="container">
    <AdminLogin />
    <EmployeeLogin />
  </section>
</template>

<script>
import AdminLogin from './components/AdminLogin.vue'
import EmployeeLogin from './components/EmployeeLogin.vue'

export default {
  name: 'App',
  components: {
    AdminLogin,
    EmployeeLogin
  }
}
</script>
