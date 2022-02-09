<template>
  <div>
    <img :src="comic.thumb" alt="comic.series" class="h-100 p-3" />
  </div>
</template>

<script>
export default {
  props: ["comic"],
};
</script>

<style lang="scss" scoped>
</style>