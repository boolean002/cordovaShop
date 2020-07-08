<template>
  <div id="app">
    <router-view/>
    <navigate/>
  </div>
</template>

<script>
import './assets/style/common.css';
import navigate from './components/footer/navigate.vue'
export default {
  name: 'app',
  components:{
        navigate
    }
}
</script>


