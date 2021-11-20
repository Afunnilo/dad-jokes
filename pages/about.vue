<template>
  <div>
      <h1>About Dad Jokes</h1>
      <p>App that dispays dad jokes, made with NUXTJS</p>
      <ul>
          <li>
              <a class='link' href="https://icanhazdadjoke.com/api" target='_blank'>API source</a>
          </li>
          <li>
              <a class='link' href="https://github.com/Afunnilo/dad-jokes" target='_blank'>Github repo</a>
          </li>
      </ul>
  </div>
</template>

<script>
export default {
    head() {
        return{
            title:'About The App',
            meta: [
                {
                    hid:'description', //unique identifier
                    name:'descrption',
                    content:'Best place for corny dad jokes'
                }
            ]
        }
    }
}
</script>

<style>
.link{
   font-size: 20px;
}
</style>