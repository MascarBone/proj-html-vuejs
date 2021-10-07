<template>
  <div>
        <span v-for="(el, i) in info" :key="i">
            <a :href="el.src" v-if="el.id == 'link'">{{el.descr}}</a>
            <span v-else>{{el.descr}}</span>
        </span>
  </div>
</template>

<script>
export default {
    name: 'FootCopyright',

    props: {
        info: Array,
    }

}
</script>

<style scoped lang="scss">
@import '../../style/variables.scss';

a {
    color: $white;
}

</style>