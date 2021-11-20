<template>
<nuxt-link :to="'jokes/' +id">
  <div class="joke">
      <p>{{joke}}</p>
  </div>
</nuxt-link>
</template>

<script>
export default {
    name:'Joke',
    props: ['joke', 'id']
}
</script>

<style>
.joke{
    padding:1rem;
    border-top:1px solid #4682B4;
}
.joke:hover{
    border: 1px solid #4682B4;
    background: #4682B4;
    border-radius:5px;
    border-bottom: 0;
}
</style>