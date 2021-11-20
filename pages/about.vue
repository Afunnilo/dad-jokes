<template>
  <div>
      <h1>About Dad Jokes</h1>
      <p>This is an app that displays dad jokes</p>
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

</style>