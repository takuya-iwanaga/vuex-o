<template >
  <div class="home">
    <counter></counter>
  </div>
</template>
<script>
  import counter from "@/counter.vue";

  export default{
    name: "home",
    components: {
      counter
    }
  };
</script>
