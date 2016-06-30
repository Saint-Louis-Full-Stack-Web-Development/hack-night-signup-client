<script>
    let state = require('./state.js')

    module.exports = {
        data: () => {
            return {
                member: state,
                status: true
            }
        },
        methods:{
            submit: function (){
                console.log(this.member)
                alert('submitted')
            }
        }
    }
</script>

<template>
    <div class="action-container well">
        <button v-on:click="submit" type="button" class="btn btn-primary">Submit</button>
    </div>
</template>

<style lang="sass">

    .action-container{
    }
</style>