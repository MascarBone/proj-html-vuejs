<template>
  <div class="d-flex">
      <div class="wrap me-4" v-for="(plan, i) in plans" :key="i">
        <i :class="plan.icon" class="me-1"></i>
        <span>{{plan.descr}}</span>
      </div>
  </div>
</template>

<script>
export default {
  name: 'Plans',

  data: function() {
    return {
      // List of plans aviable with relative icon of FontAwesome
      plans: [
        {icon : 'fas fa-briefcase'  , descr:  'Become an Instructor'},
        {icon : 'fas fa-bullhorn'   , descr:  'For Enterprise'},
      ]
    }
  }
}
</script>

<style scoped lang="scss">
@import '../../style/general.scss';

  .wrap {
    @include flex-align-center;

  }
</style>