<template>
  <div class="skills-content">
    <Card />
  </div>
</template>

<script>
import Card from './Card';

export default {
  components: {
    Card,
  },
};
</script>

<style scoped>
.skills-content {
  height: calc(100% - 6rem);
}
</style>
