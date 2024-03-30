<template>
  <TrexGame />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import TrexGame from "@/components/TrexGame.vue"; // @ is an alias to /src

export default defineComponent({
  name: "TrexGame",
  components: {
    TrexGame,
  },
});
</script>
