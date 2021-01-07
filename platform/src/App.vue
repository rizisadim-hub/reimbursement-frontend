<template>
  <section class="container-fluid">
    <!-- <AdminLogin />
    <EmployeeLogin /> -->
    <ReimbursementList />

  </section>
</template>

<script>
// import AdminLogin from './components/AdminLogin.vue'
// import EmployeeLogin from './components/EmployeeLogin.vue'
// import EmployeeLogin from './components/EmployeeLogin.vue'
import ReimbursementList from './components/ReimbursementList.vue';
export default {
  name: 'App',
  components: {
    // AdminLogin,
    // EmployeeLogin
    ReimbursementList
  }
}
</script>
