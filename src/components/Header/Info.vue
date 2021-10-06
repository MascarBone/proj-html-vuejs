<template>
  <div class="info-wrap">
      <div v-for="(opt, i) in options" :key="i">
          <div>{{opt.name}}</div>
      </div>
  </div>
</template>

<script>

export default {
    name: 'Info',

    data: function() {
        return {
            options: [
                {
                    link: '#',
                    name: 'Home',
                },
                {
                    link: '#',
                    name: 'Pages',
                },
                {
                    link: '#',
                    name: 'Course Formats',
                },
                {
                    link: '#',
                    name: 'Courses',
                },
                {
                    link: '#',
                    name: 'Demos',
                }
            ]
        }
    }
}
</script>

<style scoped lang="scss">
    .info-wrap {
        display: flex;

        > *{
            display: flex;
            margin: 0 15px;
        }
    }

</style>