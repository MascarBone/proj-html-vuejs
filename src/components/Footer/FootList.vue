<template>
  <div>
        <h5>{{info.heading}}</h5>
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
h5 {
    text-transform: uppercase;
}

</style>