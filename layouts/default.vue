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
  background:#f4f4f4;
}
a{
  color:#666;
  text-decoration: none;
}
ul{
  list-style-type: none;
}
.container{
  max-width: 800px;
  margin:2em auto;
  overflow:hidden;
  padding:1rem 2rem;
  background: #fff;

}
</style>