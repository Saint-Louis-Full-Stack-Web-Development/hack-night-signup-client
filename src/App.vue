<template>
  <div class="container">
    <signups></signups>
    <member></member>
    <actions></actions>
  </div>
</template>

<script>
import Actions from './components/Actions.vue'
import Member from './components/Member.vue'
import Signups from './components/Signups.vue'

export default {
  components: {
    Actions, Member, Signups
  },
  data () {
    return {
    }
  }
}
</script>

<style lang="sass">
@import "./main.scss";
body {
  font-family: Helvetica, sans-serif;
}
</style>
