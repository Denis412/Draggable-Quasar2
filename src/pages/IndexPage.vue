<template>
  <q-page class="flex flex-center">
    <DragTest />
  </q-page>
</template>

<script>
import { defineComponent } from "vue";
import DragTest from "src/components/DragTest.vue";

export default defineComponent({
  name: "IndexPage",
  components: {
    DragTest,
  },
});
</script>
