<template>
  <div class="container-fluid">
    <h5 class="display-5">This is the homepage!</h5>
    <dashboard></dashboard>
  </div>
</template>

<script>
// @ is an alias to /src
import Dashboard from "@/components/Dashboard.vue";

export default {
  name: "Home",
  components: {
    Dashboard
  }
};
</script>
