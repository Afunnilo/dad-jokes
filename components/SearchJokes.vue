<template>
  <form @submit.prevent='onSubmit'>
      <input  class ='text-box' type="text" v-model='text' placeholder="Search Jokes..." >
      <input class='btn' type="submit" value='Search Jokes'>
  </form>
</template>

<script>
export default {
    name:'SearchJokes',
    data() {
        return{
            text:''
        }
    },
    methods:{
        onSubmit(){
            this.$emit('search-text', this.text);
            this.text = ""
        }
    }
}
</script>

<style>
.text-box{
    padding: 10px 10px;
}
.btn{
     padding: 10px 10px;
     background: #4682B4 ;
     border: 1px solid #4682B4;
     border-radius: 5px;

}
form{
    text-align: center;
    padding-bottom: 15px;
}
</style>