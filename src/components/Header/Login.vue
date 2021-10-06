<template>
  <div class="wrap">
    <div class="login me-4">
      <i :class="logInfo.icon" class="me-1"></i>
      <span>{{logInfo.name}}</span>
    </div>
    <div class="signup me-4">
      <a :href="btnInfo.link"><button>{{btnInfo.name}}</button></a>
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
@import '../../style/variables.scss';

.wrap {
  @include flex-align-center;

}

.login {
  @include flex-align-center;
}

.signup {

  button {
    border: none;
    border-radius: 50px;
    background-color: $coral-red;
    color: $white;
    font-size: 1.2rem;
    font-weight: 600;
    padding: 15px 30px;
    text-transform: uppercase;
  }
}
</style>