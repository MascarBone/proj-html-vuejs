<template>
  <div class="row">
      <h3 class="col-12">{{info.heading}}</h3>
      <div v-for="el in info.list" :key="el.id" class="col-3">
          <i :class="el.src" class="fa-3x"></i>
      </div>
  </div>
</template>

<script>
export default {
    name: 'FootSocials',

    props: {
        info: Object,
    }

}
</script>

<style scoped lang="scss">
h3 {
    text-transform: uppercase;
}
</style>