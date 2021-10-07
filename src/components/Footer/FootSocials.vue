<template>
  <div class="row gy-3">
      <h3 class="col-12">{{info.heading}}</h3>
      <div v-for="el in info.list" :key="el.id" class="col-3">
          <div class="box-icon" :style="{background:el.color}">
              <i :class="el.src"></i>
          </div>          
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
.box-icon {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 60px;
    height: 60px;
    border-radius: 50%;

    i {
        font-size: 1.6rem;
    }
}
</style>