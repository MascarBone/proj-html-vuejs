<template>
  <div>
      <img :src="info.src" :alt="info.id">
  </div>
</template>

<script>
export default {
    name: 'FootLogo',

    props: {
        info: Object,
    }

}
</script>

<style scoped>
img {
    max-width: 100%;
}

</style>