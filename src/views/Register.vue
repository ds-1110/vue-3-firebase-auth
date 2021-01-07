<template>
  <div class="container-fluid d-flex justify-content-center align-items-center flex-column">
      <h4 class="display-4 my-5"><u>Register Page</u></h4>
      <register-form></register-form>
  </div>
</template>

<script>
import RegisterForm from "@/components/RegisterForm.vue"
export default {
    components: {
        RegisterForm
    }
}
</script>

<style>

</style>