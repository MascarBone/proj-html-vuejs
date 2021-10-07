<template>
    <header>
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
        </div>

        <div>
            <hr>
        </div>

        <div class="container">
            <div class="row header-bot">
                <div class="col-auto">
                    <Logoheader />
                </div>
                <div class="col-auto">
                    <Category />
                </div>
                <div class="col">
                    <Searchbar />
                </div>
                <div class="col-auto">
                    <Plans />
                </div>
                <div class="col-auto">
                    <Login />
                </div>
            </div>
        </div>
    </header>
</template>

<script>
import Languages from './Header/Languages.vue';
import Info from './Header/Info.vue';
import Icons from './Header/Icons.vue';
import Logoheader from './Header/Logoheader.vue';
import Category from './Header/Category.vue';
import Searchbar from './Header/Searchbar.vue';
import Plans from './Header/Plans.vue';
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
        Plans,
        Login,
    }

}
</script>

<style scoped lang="scss">
@import '../style/variables.scss';

    .row {
        align-items: center;
    }
    .header-top {
        padding-top:  20px;
        color: $venus;
    }
</style>