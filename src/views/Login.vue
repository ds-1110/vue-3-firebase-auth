<template>
  <div class="container-fluid d-flex justify-content-center align-items-center flex-column">
      <h4 class="display-4 my-5"><u>Login Page</u></h4>
      <login-form></login-form>
  </div>
</template>

<script>
import LoginForm from "@/components/LoginForm.vue"
export default {
    components: {
        LoginForm
    }
}
</script>

<style>

</style>