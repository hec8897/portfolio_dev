<template>
  <div id="app">
    <Header/>
    <router-view/>
  </div>
</template>

<script>
import Header from './common/Header';
export default {
  name:'App',
  components:{
    Header
  }
}
</script>

<style lang="scss">
@import './define.scss';

</style>
