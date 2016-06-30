<script>
    let state = require('./state.js')
    console.log(state)
    module.exports = {
        data: () => {
            return {
                member:state
            }
        }
    }
</script>

<template>
    <div class="well">
        <form>
            <div class="form-group">
                <label for="first_name">First Name</label>
                <input v-model="member.first_name" type="text" name="first_name" class="form-control">
            </div>
            <div class="form-group">
                <label for="last_name">Last Name</label>
                <input v-model="member.last_name" type="text" name="last_name" class="form-control">
            </div>
            <div class="form-group">
                <label for="email">Email</label>
                <input v-model="member.email" type="text" name="email" class="form-control">
            </div>
        </form>
    </div>
</template>

<style lang="">
</style>