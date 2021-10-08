<template>
  <div class="wrap">
    <div class="login me-4">
      <i :class="logInfo.icon" class="me-1"></i>
      <span>{{logInfo.name}}</span>
    </div>
    <div class="signup me-4">
      <a :href="btnInfo.link"><button class="my_btn-primary">{{btnInfo.name}}</button></a>
    </div>
    <div>
      <i class="fas fa-cookie"></i>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Login',

  data: function() {
    return {
      logInfo: {
        icon: 'far fa-user',
        name: 'Log in',
      },

      btnInfo: {
        name: 'Sign up',
        link: '#',
      }

    }
  }
}
</script>

<style scoped lang="scss">
@import '../../style/general.scss';

.wrap {
  @include flex-align-center;

}

.login {
  @include flex-align-center;
}

</style>