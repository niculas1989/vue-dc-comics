<template>
  <div>
    <div class="text-center">
      <img :src="comic.thumb" class="card-img-top m-3" :alt="comic.series" />
      <p class="">{{ comic.series.toUpperCase() }}</p>
    </div>
  </div>
</template>

<script>
export default {
  props: ["comic"],
};
</script>

<style lang="scss" scoped>
img {
  height: 230px;
  width: 230px;
}

p {
  color: white;
}
</style>