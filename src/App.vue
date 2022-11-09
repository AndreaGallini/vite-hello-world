<template>
  <div>
    <AppTitle />
    <JumboComponent />
  </div>
</template>

<script>
import JumboComponent from "./components/JumboComponent.vue";
import AppTitle from "./components/AppTitle.vue";

export default {
  components: {
    AppTitle,
    JumboComponent,
  },
};
</script>

<style lang="scss" scoped></style>
