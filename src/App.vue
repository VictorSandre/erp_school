<template>
  <div id="app">
  </div>
</template>

<script>
import Vue from 'vue';
import Vuex from 'vuex';
import store from './Plugins/store/store'

Vue.use(Vuex);

export default {
  name: 'app',
  store: store,
  data () {
    return {}
  }
}
</script>
