<template>
<div class ='container'>
<AppHeader />
  <nuxt/>
</div>
  
</template>
<script>
import AppHeader from '../components/AppHeader.vue'
export default {
  components:{
    AppHeader
  }
}
</script>

<style>
*{
  box-sizing:border-box;
  margin:0;
  padding:0;
}
body{
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  font-size:1rem;
  line-height:1.6;
  background: #F0F8FF;
}
a{
  color:black;
  text-decoration: none;
}
ul{
  list-style-type: none;
}
.container{
  max-width: 800px;
  margin-left: auto;
  margin-right: auto;
  overflow:hidden;
  padding:1rem 2rem;
  background: #F0F8FF;

}
</style>