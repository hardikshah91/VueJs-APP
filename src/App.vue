<template>
  <div id="app" data-server-rendered="true">
    <app-header></app-header>
    <router-view></router-view>
  </div>

</template>

<script>
import Header from './components/Header.vue';

export default {
  data() {
    return {
      selectedComponent: 'app-hot'
    }
  },
  components: {
    appHeader: Header
  }
}
</script>
