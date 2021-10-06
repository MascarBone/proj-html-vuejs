<template>
  <div class="icon-box">
      <div v-for="icon in icons" :key="icon.id">
          <i :class="icon.src"></i>
      </div>
  </div>
</template>

<script>
import icons from '../../data/icons.json';

export default {
    name: 'Icons',

    data: function() {
        return {
            icons,
        }
    }
}
</script>

<style scoped lang="scss">
    .icon-box {
        display: flex;
        > * {
            margin: 0 8px;
        }
    }
</style>