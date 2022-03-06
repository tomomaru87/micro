<template>
 
  <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
  <div id="app">

    <Header/>
    <router-view></router-view>
    <Footer/>

  </div>
</template>

<script>

import Header from './components/template/Header.vue'
import Footer from './components/template/Footer.vue'


export default {
  head:{
meta:[
  {
    name:"robots",content:"noindex"
  }
]
  },
  name: 'App',
  components: {

    Header,
    Footer,
  }
  
}
</script>


