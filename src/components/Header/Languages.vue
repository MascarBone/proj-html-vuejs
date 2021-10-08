// Component that shows a list of aviable languages through a selection
<template>
    <div>
        <!-- Select with the list of languages -->
        <select id="language" v-model="selected">
            <option v-for="lang in languages" :key="lang.id" :value="lang.id">{{lang.name}}</option>
        </select>

    </div>
</template>

<script>
export default {
    name: 'Languages',

    data: function() {
        return {
            languages: [
                {id: 'it'   ,   name: 'Italian'},
                {id: 'de'   ,   name: 'Germany'},
                {id: 'en'   ,   name: 'English'},
                {id: 'es'   ,   name: 'Spanish'},
                {id: 'ru'   ,   name: 'Russian'},
                {id: 'cn'   ,   name: 'Chinese'},
                {id: 'fr'   ,   name: 'French'},
            ],

            // v-model linked on select
            selected: 'en',

        }
    }

}
</script>

<style scoped lang="scss">
@import '../../style/variables.scss';

    select {
        background-color: none;
        border: none;
        color: $venus;
        
    }
</style>