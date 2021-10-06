<template>
  <div class="container">
      <div class="row header-top">
            <div class="col">
                <Languages />
            </div>
            <div class="col-auto">
                <Info />
            </div>
            <div class="col-auto">
                <Icons/>
            </div>
      </div>
      <div class="row">
            <Logoheader />

            <Category />

            <Searchbar />

            <Plan />

            <Login />
      </div>
  </div>
</template>

<script>
import Languages from './Header/Languages.vue';
import Info from './Header/Info.vue';
import Icons from './Header/Icons.vue';
import Logoheader from './Header/Logoheader.vue';
import Category from './Header/Category.vue';
import Searchbar from './Header/Searchbar.vue';
import Plan from './Header/Plan.vue';
import Login from './Header/Login.vue';

export default {
    name: 'Header',

    components:{
        Languages,
        Info,
        Icons,
        Logoheader,
        Category,
        Searchbar,
        Plan,
        Login,
    }

}
</script>

<style scoped lang="scss">

</style>