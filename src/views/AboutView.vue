<template>
  <div class="about">
    <h1>{{ PageName }}</h1>
    <p>{{ PageDescription }}</p>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      PageName: "amany",
      PageDescription: "Description",
    };
  },
  name: "About",
};
</script>
