<template>
    <form>
        <!-- Form for the input search -->
        <input type="textbox" v-model="search" placeholder="Search courses">
        <button type="submit">
            <span><i class="fas fa-search"></i></span>
        </button>
    </form>
</template>

<script>
export default {
    name: 'Searchbar',

    data: function() {
        return {
            search: '',
        }
    }

}
</script>

<style scoped lang="scss">
@import '../../style/variables.scss';

form {
    display: flex;
    > * {
        border: none;
        padding: 8px 15px;
    }
}
input {
    background-color: $grey;
    flex-grow: 1;
}

button {
    background-color: #457992;
    color: $white;
}
</style>