<template>
  <div>
        <h3>{{info.heading}}</h3>
        <p v-for="(el, i) in info.list" :key="i">
            {{el}}
        </p>
  </div>
</template>

<script>
export default {
    name: 'FootList',

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