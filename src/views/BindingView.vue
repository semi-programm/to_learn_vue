<template>
  <div id="vue">
    <input type="text" v-model="value" />
    <p>state: {{ value }}</p>
  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "HelloWorld",
  data() {
    return {
      value: "",
    };
  },
  created() {
    console.log("作られた");
  },
  updated() {
    console.log("update!!");
  },
});
</script>
