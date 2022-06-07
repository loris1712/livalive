<template>
  <div class="home">
    <homePart1 />
    <homePart2 />
    <homePart3 />
  </div>
</template>

<script>
// @ is an alias to /src
import homePart1 from "@/components/homePart1.vue";
import homePart2 from "@/components/homePart2.vue";
import homePart3 from "@/components/homePart3.vue";

export default {
  name: "HomeView",
  components: {
    homePart1,
    homePart2,
    homePart3,
  },
};
</script>
