<template>

  <div id="app">
    <header></header>
    <router-view></router-view>

  </div>
   
</template>

<script>
import header from './components/header.vue';
import footer from './components/footer.vue';
import companyAccount from './components/companyAccount.vue';
export default {
  name: 'app',
  components: {
    'header': header,
    'footer': footer,
    'company-account': companyAccount
  },
  data () {
    return {

    }
  }
}
</script>

<style lang="scss">
@import './styles/global'

</style>
