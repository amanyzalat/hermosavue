<template>
  <div class="container">
    <div class="row">
      <div class="col-md-4">
        <InsertForm />
      </div>
    </div>
  </div>
</template>

<script>
import InsertForm from "@/components/InsertForm.vue";

export default {
  name: "FormView",
  components: {
    InsertForm,
  },
};
</script>
