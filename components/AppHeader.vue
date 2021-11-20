<template>
  <header class="header">
      <h1 class="title">Dad Jokes</h1>
      <ul>
          <li>
              <nuxt-link to='/'>Home</nuxt-link>
          </li>
           <li>
              <nuxt-link to='/jokes'>Jokes</nuxt-link>
          </li>
           <li>
              <nuxt-link to='/about'>About</nuxt-link>
          </li>
      </ul>
  </header>
</template>

<script>
export default {
    name:'AppHeader'
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Indie+Flower&display=swap');
.header{
    display:flex;
    justify-content: space-between;
    flex-direction: column;
    align-items: center;
    margin-bottom: 1rem;
    padding-bottom: 1rem;
    border-bottom:1px dotted #ccc;
}
.header.title{
    font-size: 3rem;
    color:grey;
    
}
.header > h1{
    font-family: 'Indie Flower', cursive;
}
.header ul {
    display: flex;
}
.header a{
    display:inline-block;
    background: #333;
    color:#fff;
    padding:0.3rem 1rem;
    margin-right:0.5rem;
}
</style>