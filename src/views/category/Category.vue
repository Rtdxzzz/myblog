<template>
  <div>
    <Type :type="type"></Type>
  </div>
</template>

<script>
import Type from "@/components/content/Type";
export default {
  name: "Category",
  components: {
    Type,
  },
  directives: {},
  data() {
    return {
      type: "category",
    };
  },
  created() {},

  mounted() {},
  methods: {},
};
</script>

<style lang="scss" scoped>
</style>