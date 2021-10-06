<template>
  <div>
      <img :src="logo.src" :alt="logo.name">
  </div>
</template>

<script>
export default {
  name: 'Logoheader',

  data: function() {
    return {
      logo: {
        src: require('../../assets/images/icons-logos/master-study.svg'),
        name: 'Master Study Logo',
      }
    }
  }
}
</script>

<style>

</style>